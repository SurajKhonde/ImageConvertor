# ImageConvertor
# 🖼️ JPG & PNG to WebP Image Converter (Docker-based)
### A fast and efficient image converter for React or web development projects — convert your JPG or PNG files to WebP with ease using Docker.
---
## ✅ Why WebP?
- **Faster Loading** – WebP images are much smaller in size than JPG or PNG.
- **Optimized for Web** – Ideal for React apps and modern websites.
- **No Quality Loss** – WebP maintains good image quality while reducing file size.
---
## 🛠️ How to Install Docker on Ubuntu
### 1. Update existing packages:
```bash
-- sudo apt update
-- sudo apt install docker.io
```
### 3. Enable Docker to run on boot:
    sudo systemctl enable docker
### 4. Start Docker service:
  sudo systemctl start docker
 ### How to Check if Docker is Installed
```bash
docker --version
```
### 🚀 How to Use the Image Converter
##### 1. 📦 Unzip the Project
Unzip the downloaded project folder.

##### 2. 🖥️ Open Terminal in the Folder
Open your terminal in the directory where the project was unzipped.
##### 3. 🐳 Load the Docker Image
```bash
sudo docker load -i webp-converter.tar
```
##### 4. ▶️ Run the Converter Script
##### 5. 📂 Provide the Absolute Path
When asked, enter the full absolute path to the folder that contains your .jpg or .png files.
##### ⚙️ What the Script Does
✅ Converts JPG and PNG images to WebP
✅ Keeps other image formats (like .svg) unchanged
✅ Creates a new folder for converted WebP images
✅ Preserves original image files — no overwriting
###### 📁 Output Example
Original folder: ~/Pictures/gallery

Converted images: ~/Pictures/gallery-webp
## please Use this link to download .zip
https://drive.google.com/file/d/1LKtaVPK8feNFMxFg9gyC0a-QlEN1q3K2/view?usp=drive_link

