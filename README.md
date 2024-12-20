# Scikit-learn structure

---

```
Scikit-learn/
│
├── base/ - abstract base classes
│ ├── base_model.py - Định nghĩa lớp cơ sở cho việc tải dữ liệu
│ ├── base_data_loader.py - Định nghĩa lớp cơ sở cho các mô hình
│ └── base_optimizer.py - Định nghĩa lớp cơ sở cho các thuật toán tối ưu hoá
│
├── configs/ - configuration files
│ ├── config_classification.json - Cấu hình cho bài toán phân loại
│ └── config_regression.json - Cấu hình cho bài toán hồi quy
│
├── data_loader/ - anything about data loading goes here
│ └── data_loader.py - Chứa các lớp và các hàm để tải dữ liệu
│
├── data/ - default directory for storing input data
│ ├── train.csv - Dữ liệu huấn luyện
│ ├── test.csv - Dữ liệu test
│ └── val.csv - Dữ liệu để kiểm tra overfitting, underfitting
│
├── model/ - models, losses, and metrics
│ ├── **init**.py - Định nghĩa các mô hình theo tên
│ └── models.py - Chứa các lớp và hàm xây dựng mô hình
│
├── optimizers/ - optimization algorithms
│ └── optimizers.py - Chứa các thuật toán tối ưu hoá mô hình
│
├── saved/ - directory for saving trained models and logs
│ └── models/ - Trained models are saved here
│
├── utils/ - small utility functions
│ └── utils.py - Chứa các hàm tiện ích, chung, phổ biến thường dùng
│
├── wrappers/ - model wrappers and data transformations
│ ├── wrappers.py - Chứa các lớp bọc (wrapper) cho các mô hình
│ └── data_transformations.py - Chứa các hàm biến đổi dữ liệu
```

# Pytorch structure

---

```
Pytorch/
│
├── train.py - main script to start training
├── test.py - evaluation of trained model
│
├── config.json - holds configuration for training
├── parse_config.py - class to handle config file and cli options
│
├── new_project.py - initialize new project with template files
│
├── base/ - abstract base classes
│ ├── base_data_loader.py
│ ├── base_model.py
│ └── base_trainer.py
│
├── data_loader/ - anything about data loading goes here
│ └── data_loaders.py
│
├── data/ - default directory for storing input data
│
├── model/ - models, losses, and metrics
│ ├── model.py
│ ├── metric.py
│ └── loss.py
│
├── saved/
│ ├── models/ - trained models are saved here
│ └── log/ - default logdir for tensorboard and logging output
│
├── trainer/ - trainers
│ └── trainer.py
│
├── logger/ - module for tensorboard visualization and logging
│ ├── visualization.py
│ ├── logger.py
│ └── logger_config.json
│
└── utils/ - small utility functions
├── util.py
└── ...

```
