<h1 align="center">Hi 👋, I'm TungDev</h1>

<h2>Tài liệu hướng dẫn setup shopify theme, shopify app</h2>
<span>------------------------------------------------------</span>
<div>
  <div><strong>1. Init App</strong></div>
  <div>- npm init @shopify/app@latest ⇒ init new app</div>
  <div>- cd app</div>
  <div>- npm run dev ⇒ run app</div>
</div>
<div>
## 🛠️ Installation Steps
  <div>* Require</div>
  <div> - Ruby or Ruby+Devkit using RubyInstaller for Windows 2.7 or higher</div>
  <div> - Nodejs & npm</div>
  <div>1. Tạo folder chứa code, mở folder bằng visual studio code</div>
  <div>2. Mở terminal của vscode, chạy lệnh node -v, npm -v, ruby -v để check version, nếu chưa có hoặc báo lỗi thì tiến hành cài lại package đang thiếu</div>
  <div>3. Khi đã đầy đủ thư viện, package ⇒ chạy lệnh gem install shopify-cli để cài đặt cli </div>
  <div>4. Khởi tạo theme mới ⇒  shopify theme init ⇒ Nhập theme-name</div>
  <div>5. cd theme-name</div>
  <div>6. Login vào store ⇒ shopify login --store xxx.myshopify.com</div>
  <div>⇒ Gặp lỗi no store ⇒ shopify logout ⇒ shopify login ⇒ shopify login --store xxx.myshopify.com</div>
  <div>7. Preview theme trên môi trường dev ⇒ shopify theme serve</div>
  <div>8. Đẩy code theme lên git theo branc</div>
  <div>9. Connect github vs store ⇒ Mọi chỉnh sửa sẽ preview trên dev, khi hoàn thiện sẽ đẩy lên git ⇒ mọi người thấy được sự thay đổi</div>
  <div>+ Có thể push code lên 1 theme có sẵn trên store bằng cli ⇒ shopify theme push  hoặc shopify theme publish (sẽ publish theme sau khi push) ⇒ push lâu + mất time</div>
  <div>+ Pull code từ 1 theme có sẵn ⇒ shopify theme pull</div>
</div>
