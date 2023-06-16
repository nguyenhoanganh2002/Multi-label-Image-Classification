# Multi-label-Image-Classification
This repo contains codes for fine tuning ResNet50 on multi-label image dataset
### Ngôn ngữ/ Thư viện/ Framework:
* Python
* Pytorch
* Matplotlib
### Tập dữ liệu:
Bộ dữ liệu gồm hơn 300 ảnh (250 cho tập huấn luyến và phần còn lại cho tập kiểm thử) về các địa điểm du lịch ở Hồ Gươm và Hồ Tây. Các hình ảnh được chia thành 2 khu vực Hồ Gươm và Hồ Tây cùng được gán đa nhãn như sau:
HoGuom : HG,
HoTay : HT,
ThapRua : TR,
CauTheHuc : CTH,
BuuDien : BD,
VuonHoa : VH,
ChuaTranQuoc : CTQ,
DenQuanThanh : DQT,
KhachSan : KS,
CongVienNuoc : CVN
* Tập huấn luyện: https://drive.google.com/drive/folders/10Y3ZRDnZ3KIT3cFRpol5EV4V614ZTmg-?usp=sharing
* Tập kiểm thử: https://drive.google.com/drive/folders/105hB6_wPCV_ztkDrEMcKbEKZjbYmO1n2?usp=sharing
### Tinh chỉnh lại mô hình Resnet50 sao cho phù hợp với bài toán
![image](https://github.com/nguyenhoanganh2002/Multi-label-Image-Classification/assets/79850337/e57df669-0858-456f-8f22-a5c8b74aaccf)
### Kết quả: mô hình đạt độ chính xác nhị phân 97% (binary accuracy) trên tập kiểm thử 
![image](https://github.com/nguyenhoanganh2002/Multi-label-Image-Classification/assets/79850337/a0b1acb5-ed7c-4147-b0ec-6e7514479755)
* Chạy thử mô hình:

![image](https://github.com/nguyenhoanganh2002/Multi-label-Image-Classification/assets/79850337/7fdc4f72-3e92-4a25-9e33-f9b7e9fe78dd)
