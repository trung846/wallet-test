
# Wallet Test

Wallet Test là một dự án thử nghiệm tích hợp ví Aptos vào một ứng dụng web được xây dựng bằng Next.js. Dự án giúp người dùng kết nối ví, kiểm tra số dư và thực hiện các giao dịch trên blockchain Aptos.

## 🛠 Công nghệ sử dụng

-   **Next.js** - Framework React để xây dựng giao diện web.
    
-   **Aptos SDK** - Thư viện để tương tác với blockchain Aptos.
    
-   **TypeScript** - Ngôn ngữ lập trình mạnh mẽ giúp viết code an toàn hơn.
    
-   **Tailwind CSS** - Framework CSS để tạo giao diện đẹp và dễ tùy chỉnh.
    

## 🚀 Cài đặt

### Yêu cầu hệ thống

-   Node.js (>= 16.0)
    
-   Git
    
-   Aptos Wallet (Petra, Martian, Pontem,...)
    

### Cách chạy dự án

1.  **Clone repository**
    
    ```
    git clone https://github.com/your-username/wallet-test.git
    cd wallet-test
    ```
    
2.  **Cài đặt dependencies**
    
    ```
    npm install
    ```
    
    hoặc
    
    ```
    yarn install
    ```
    
3.  **Cấu hình môi trường**
    
    -   Tạo file `.env.local` và thêm thông tin như sau:
        
        ```
        NEXT_PUBLIC_APTOS_NODE_URL=https://fullnode.testnet.aptoslabs.com/v1
        NEXT_PUBLIC_WALLET_PROVIDER=petra
        ```
        
4.  **Chạy ứng dụng**
    
    ```
    npm run dev
    ```
    
    hoặc
    
    ```
    yarn dev
    ```
    
    Mở trình duyệt và truy cập `http://localhost:3000` để xem ứng dụng.
    

## 📌 Tính năng

-   Kết nối ví Aptos (Petra, Martian, Pontem,...).
    
-   Hiển thị số dư tài khoản.
    
-   Gửi và nhận token APT.
    
-   Tích hợp với Aptos SDK để tương tác với smart contract.
    

## 🛠 Triển khai

Bạn có thể triển khai dự án lên **Vercel** bằng cách:

```
vercel
```

Hoặc deploy lên **Netlify**:

```
netlify deploy
```

## 📜 Giấy phép

Dự án được phát hành theo giấy phép MIT.
