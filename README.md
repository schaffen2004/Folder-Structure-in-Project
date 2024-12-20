# Scikit-learn structure

---

1. base

- **base_model.py**: định nghĩa lớp cơ sở cho việc tải dữ liệu
- **base_data_loader.py**: định nghĩa lớp cơ sở cho các mô hình
- **base_optimizer.py**: định nghĩa lớp cơ sở cho các thuật toán tối ưu hoá

2. configs

- **config_classification.json**: lưu cấu hình cho bài toán phân loại
- **config_regression**: lưu cấu hình cho bài toán hồi quy

3. data loader

- **data_loader.py**: chứa các lớp và các hàm để tải dữ liệu

4. model

- **init.py**: định nghĩa các mô hình theo tến
- **models.py**: chứa các lớp và hàm xây dựng mô hình

5. optimizers

- **optimizers.py**: chứa các thuật toán tối ưu hoá mô hình

6. saved

7. utils

- **utils.py**: chứa các hàm tiện ích, chung, phổ biến thường dùng

8. data

- **train.csv**: dữ liệu huấn luyện
- **test.csv**: dữ liệu test
- **val.csv**: dữ liệu để check overfitting, underfitting

9.  wrappers

- **wrappers.py**: chứa các lớp bọc (wrapper) cho các mô hình
- **data_transformations.py**: chứa các hàm biến đổi dữ liệu

# Pytorch structure

---
