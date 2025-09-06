# AllInOneVoice - Auto-Update System

Đây là repository chứa hệ thống auto-update cho Voice Generation Application.

## Version Info

Repository này chỉ chứa:
- `version.json` - Thông tin phiên bản hiện tại
- `app.zip` - Package ứng dụng (trong Releases)

## How Auto-Update Works

1. App kiểm tra `version.json` trên GitHub
2. So sánh với version local
3. Nếu có version mới → download `app.zip` từ Releases
4. Tự động cập nhật và restart

## For Users

- Download app từ [Releases](https://github.com/nguyentruongduy1410/AllInOneVoice/releases/latest)
- Extract và chạy `start.bat`
- App sẽ tự động update khi có version mới

## For Developers

Repository này KHÔNG chứa source code chính, chỉ là update server.

## Contact

- Developer: Nguyễn Trường Duy
- Phone: 0962615032
