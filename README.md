# Docker-Compose
# Bài 1: Chạy một container đơn giản với Docker Compose, Yêu cầu:
- Tạo một container chạy Nginx bằng Docker Compose.
- Map cổng 8080 của máy host với cổng 80 của container.
  
![image](https://github.com/user-attachments/assets/a9572e6b-2b6e-4447-b123-3caf579a8ba4)
- File cấu hình docker-compose với
container_name: my_nginx (tên của container), 
ports: - "8080:80" (Map 2 cổng 8080 với 80 lại với nhau )
![image](https://github.com/user-attachments/assets/118d6164-7467-455b-a696-8bf051ef4e5d)
- Chạy lệnh docker-compose up -d để chạy cấu file yml 

# Bài 2: Chạy MySQL với Docker Compose
- Tạo một container chạy MySQL phiên bản 8.0.
- Đặt username là user, password là password và database là mydb

![image](https://github.com/user-attachments/assets/546182ab-5cc5-4861-b085-6f24688e06c6)

( File cấu hình cho docker compose với MySql )
![image](https://github.com/user-attachments/assets/155f0898-1c41-4dfc-a0c2-042d641eba7b)

( Chạy lệnh để khởi tạo container MySql đã được cấu hình trước đó )
![image](https://github.com/user-attachments/assets/7b508b8a-4ef3-4216-976c-32d350330ce9)

( Các container có trong docker desktop )

# Bài 3: Kết nối MySQL với PHPMyAdmin
- Chạy MySQL và PHPMyAdmin với Docker Compose.
- PHPMyAdmin chạy trên cổng 8081.

![image](https://github.com/user-attachments/assets/eb939e74-59fe-470c-891c-145013754321)

( File cấu hình docker compose )
![image](https://github.com/user-attachments/assets/3b1cdb36-a2cd-47cd-9a21-66f0f6e6b04a)

( Chạy lệnh docker-compose up -d để tạo container )
![image](https://github.com/user-attachments/assets/5152d4b4-d099-43f2-b850-e8dd3b3c4ec3)




