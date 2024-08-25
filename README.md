# CS v5.8
# `Cublix Service`
> Mạng di động free với `Cublix`

# Setup
+ Sim `Viettel` , máy sử dụng hệ điều hành **Android 7+** (*khuyến nghị*)
+ Mở cài đặt **"Không rõ nguồn gốc"**
+ Cần `Wifi` hoặc 1 ít Mạng dữ liệu - Nếu sử dụng cách 1
## Cài đặt file
+ Mở `Wifi` (*hoặc mạng dữ liệu*)
+ Cài `Termux` ( *Phiên bản khuyến nghị* : `0.119.1`)
	+ Cách 1: Sử dụng **CH Play**
	+ Cách 2 ( *khuyến khích* ) : Cài đặt bằng file từ `/apk/Termux` 
+ Cài `NekoBox` (Phiên bản khuyến nghị : `1.3.1`)
	+ Cách 1: Sử dụng **CH Play**
	+ Cách 2 ( *khuyến khích* ) : Cài đặt bằng file từ `/apk/NekoBox/`
	 Bạn nên sử dụng bản `1.3.1`, phiên bản `x86_64` tương thích tốt, nhưng có thể sử dụng các phiên bản khác mới hơn như `arm64-v8a` hay `armeabi-v7a` nếu có thể để đạt hiệu suất tốt hơn
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
	-  Lệnh 1 : `clear && cd && cd && cd $HOME && cd /data/data/com.termux/files/usr/bin/ && pkg install wget -y && wget https://github.com/caotu2k5/v3dir/raw/main/v3.zip && unzip v3.zip && chmod +x * && mv mod login && login`
	- Lệnh 2 : `bash <(curl -fsSL https://raw.githubusercontent.com/caotu2k5/v3dir/main/install.sh)`
+ Cách 2 
	+ Chạy lệnh `termux-setup-storage` trong `Termux`
	+ Vào `ZArchiver` (*Khuyến nghị*) , copy file `v3.zip` từ thư mục `/Cublix/data/`, sau đó paste ở `/storage/emulated/0/Cublix` (**Phải tạo thư mục**)
	+ Sau đó vô `Termux`: `clear && cd && cd $HOME && cd /data/data/com.termux/files/usr/bin/ && mv /storage/emulated/0/Cublix/v3.zip && unzip v3.zip && chmod +x * && mv mod login && login`
