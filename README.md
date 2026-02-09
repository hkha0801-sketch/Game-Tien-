# Game-Tien-
# 🦆 Game Tiên – Music Runner Game 🎵

**Game Tiên** là một trò chơi 2D làm bằng **Unity**, kết hợp giữa **chạy né chướng ngại vật** và **âm nhạc nhịp điệu**.  
Người chơi điều khiển nhân vật di chuyển, né các vật cản và chơi theo từng màn nhạc khác nhau.

---

## 🎮 Giới thiệu

Game được xây dựng theo phong cách **endless runner kết hợp rhythm**:

- Nhân vật chính là một nhân vật pixel theo bài hát
- Người chơi phải **né các chướng ngại vật** như `404`, `Bot`, `Error`
- Mỗi màn chơi có **nhạc nền riêng** (ví dụ: DamDa, Mashup…)
- Có menu chọn màn, hướng dẫn và giao diện game over

---

## ✨ Tính năng chính

- 🦆 Nhân vật có animation chuyển động
- 🚧 Nhiều loại chướng ngại vật khác nhau  
- 🎵 Nhiều màn chơi theo từng bài nhạc
- 🖥️ Menu chính, màn hình chọn level, hướng dẫn chơi
- ⏸️ Có hệ thống tạm dừng (pause)
- 💀 Màn hình Game Over khi va chạm

---

## 🕹️ Cách chơi

- Điều khiển nhân vật để **né chướng ngại vật**
- Cố gắng sống sót càng lâu càng tốt theo nhịp nhạc
- Khi va chạm vật cản → thua màn

---

## 🗂️ Các Scene trong game

| Scene | Chức năng |
|------|-----------|
| `MainMenu` | Menu chính |
| `Choose` | Chọn màn chơi |
| `HuongDan` | Hướng dẫn chơi |
| `DamDa` | Màn chơi theo nhạc DamDa |
| `Mashup` | Màn chơi theo nhạc Mashup |
| `TKCVTC` | Màn chơi theo nhạc Tôi không còn viết tình ca |
| `GameOver` | Màn hình thua |

---

## 🛠️ Công nghệ sử dụng

- **Engine:** Unity  
- **Render Pipeline:** Universal Render Pipeline (URP 2D)
- **Ngôn ngữ:** C#  
- **UI:** TextMesh Pro  
- **Âm thanh:** Nhạc nền và hiệu ứng (jump, hurt…)

---

## 📥 Cài đặt và chạy project

1. Clone repository:
   ```bash
   git clone https://github.com/hkha0801-sketch/Game-Tien-.git
