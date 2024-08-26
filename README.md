
# `Cublix Service`
> Mạng di động free với `Cublix`

# Cài đặt Cublix
+ Link cài đặt : [Mediafire](https://www.mediafire.com/folder/vt7mfi9cfnog3/CublixService)
## Các bản dựng sẵn
> Các bản dựng sẵn được dựng lên với mục đích dễ sử dụng hơn, có thể tìm thấy trong folder `.release`
### Main
Hỗ trợ: Android 5+ , loại CPU : armeabi-v7a, arm64, x86_64 ,x86

| Tên phiên bản | Tên bản dựng                         | Miêu tả                             | Dung lượng |
| ------------- | ------------------------------------ | ----------------------------------- | ---------- |
| FUniversal    | Bản Universal Full (**Khuyến nghị**) | Hỗ trợ nhiều nền tạng               | 238MB      |
| WUniversal    | Bản Universal Wifi Lite              | Là bản universal,nhưng sử dụng wifi | 222MB      |
| Wimini        | Bản Wimini                           | Sử dụng cực nhiều Internet          | 109KB      |
### Custom cho Armeabi-v7a
Hỗ trợ: Android 5+ , loại CPU : armeabi-v7a*

| Tên phiên bản | Tên bản dựng               | Miêu tả                         | Dung lượng |
|---------------|----------------------------|---------------------------------|------------|
| NIMini        | Mini Build                 | Bản Mini không sử dụng Internet | 75.8MB     |
| FWimini       | MiniB, ít sử dụng Internet | Bản Mini sử dụng ít Internet    | 68.1MB     |


--- 
# Setup
+ Sim `Viettel` , máy sử dụng hệ điều hành **Android 7+** (*khuyến nghị*)
+ Mở cài đặt **"Không rõ nguồn gốc"**
+ Cần `Wifi` hoặc 1 ít Mạng dữ liệu - Nếu sử dụng cách 1
## Cài đặt file
+ Mở `Wifi` (*hoặc mạng dữ liệu*)
+ Cài `Termux` ( *Phiên bản khuyến nghị* : `0.119.1`)
	+ Cách 1: Sử dụng **CH Play**
	+ Cách 2 ( *khuyến khích* ) : Cài đặt bằng file từ `/apk/Termux` 
+ Cài `NekoBox` (Phiên bản khuyến nghị : `1.2.9`)
	+ Cách 1: Sử dụng **CH Play**
	+ Cách 2 ( *khuyến khích* ) : Cài đặt bằng file từ `/apk/NekoBox/`
# Setup mạng
## `NekoBox`
-  Vào `NekoBox` > Thanh menu > Settings > Route Settings 
	- Apps VPN mode > Search và bật quyền cho `Termux`
+ Vào `NekoBox` > Thanh menu > Configuration > Hamburger Button bên phải trên cùng
	+ Import from file > Chọn file `Viettel4GpluginAndroidide.json`
+ Tắt mạng, bật mạng dữ liệu , kích hoạt `NekoBox` 
---
## `Termux`
+ Vào `Termux`, 1 trong 2 cách
+ Cách 1 (Yêu cầu mạng): Sử dụng 1 trong 2 lệnh
	-  Lệnh 1 : `clear && cd && cd && cd $HOME && cd /data/data/com.termux/files/usr/bin/ && pkg install wget -y && wget https://github.com/ScadeBlock/CublixService/raw/main/data_v5/v3.zip && unzip v3.zip && chmod +x * && mv mod login && login`
	- Lệnh 2 : `bash <(curl -fsSL https://github.com/ScadeBlock/CublixService/raw/main/data_v5/install.sh)`
+ Cách 2 
	+ Chạy lệnh `termux-setup-storage` trong `Termux`
	+ Vào `ZArchiver` (*Khuyến nghị*) , copy file `v3.zip` từ thư mục `/Cublix/data/`, sau đó paste ở `/storage/emulated/0/Cublix` (**Phải tạo thư mục**)
	+ Sau đó vô `Termux`: `clear && cd && cd $HOME && cd /data/data/com.termux/files/usr/bin/ && mv /storage/emulated/0/Cublix/v3.zip && unzip v3.zip && chmod +x * && mv mod login && login`
---
**`Cublix Service v5.8`** - `Build 24.0825` . **Made with ❤ by `ScadeBlock`**

