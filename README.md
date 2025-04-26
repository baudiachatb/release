# Cài đặt schema-gen plugin
```sh
    helm plugin install https://github.com/karuppiah7890/helm-schema-gen
    helm schema-gen values.yaml > values.schema.json
```

# Đóng gói helm 
```sh
    helm package .\springboot-template\ -d .\releases\
```

# Index repo
```sh
    helm repo index .
```

# Đẩy source lên github.
> địa chỉ repo là đường dẫn đến thư mục chứa file index vừa tạo ở trên.

> VD: ĐƯờng dẫn trên github là: 
```sh
    https://github.com/baudiachatb/release nhánh dev
```
> Thì đường dãn repo sẽ là:
```sh
    https://raw.githubusercontent.com/baudiachatb/release/dev
```
