[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://lazying.art)

# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-3776ab?style=for-the-badge&logo=apache&logoColor=white)](./LICENSE)
![Focus: Documentation-First](https://img.shields.io/badge/Focus-Documentation--First-FCA121?style=for-the-badge)
![Repository Stage](https://img.shields.io/badge/Stage-Early--Stage-lightgrey?style=for-the-badge)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Repository-Documentation%20First-0f766e?style=for-the-badge&logo=markdown&logoColor=white)
![Audience](https://img.shields.io/badge/Audience-Researchers%20%26%20Contributors-22c55e?style=for-the-badge&logo=google-translate&logoColor=white)

---

Kho lưu trữ cho các tài liệu dự án **Event-assisted Holographic Imaging**.

> Bản mô tả dự án gốc được giữ nguyên (chuẩn mực gốc):
> `The repo for the paper Event-assited Holographic Imaging`

## 🧭 Điều hướng nhanh

| Khu vực | Liên kết |
|---|---|
| 🎯 Tổng quan | [Tổng quan](#tổng-quan-) |
| 🗂️ Phạm vi | [Cấu trúc dự án](#cấu-trúc-dự-án-) |
| ✅ Tiêu chuẩn ban đầu | [Yêu cầu](#yêu-cầu-) |
| ▶️ Cách sử dụng | [Cách sử dụng](#cách-sử-dụng-) |
| 🧪 Đóng góp | [Đóng góp](#đóng-góp-) |
| ❤️ Support | [❤️ Support](#-support) |
| 📜 Giấy phép | [Giấy phép](#giấy-phép-) |

## Tổng quan 🔍

`EventHolography` là một kho lưu trữ **documentation-first** dành cho chủ đề tài liệu của dự án **Event-assisted Holographic Imaging**.

Tính đến thời điểm snapshot của kho này, nó được thiết kế như một trung tâm giới thiệu và truyền thông hơn là một package có thể chạy ngay.

- Trạng thái chuẩn: khung tài liệu nghiên cứu giai đoạn đầu
- Mục tiêu công khai: bối cảnh bài báo, giả định thiết lập, và hướng dẫn đa ngôn ngữ
- Phạm vi: cấu trúc kho, quy trình đóng góp, và mức sẵn sàng cho đóng góp mã dữ liệu trong tương lai

## Bức tranh nhanh về kho 📈

| Mục | Chi tiết | Trạng thái |
|---|---|---|
| `README.md` | Tài liệu dự án chính | Có và đang được duy trì tích cực |
| `LICENSE` | Điều khoản pháp lý và chính sách tái sử dụng | Apache License 2.0 |
| `.gitignore` | Quy tắc bỏ qua cho các tệp địa phương/build | Có |
| `i18n/` | Tệp README theo ngôn ngữ | Có |
| `.auto-readme-work/` | Siêu dữ liệu pipeline cho việc sinh README | Tạo ra trong quá trình soạn thảo |

## Tính năng ✨

- Xác định rõ bản sắc cho tài liệu dự án Event-assisted Holographic Imaging
- Giấy phép Apache 2.0 cho việc tái sử dụng mở và linh hoạt
- Bố cục README sẵn sàng cho quốc tế hóa qua `i18n/`
- Truyền đạt rõ trạng thái documentation-first cho người dùng và người đóng góp
- Cấu trúc tương thích với việc bổ sung sau này cho datasets, scripts, checkpoints và hướng dẫn tái lập

## Cấu trúc dự án 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

Ghi chú:

- `i18n/` chứa các phiên bản README đã dịch, bao gồm tiếng Ả Rập, tiếng Nga và các ngôn ngữ khác.
- `.auto-readme-work/` được tạo ra trong workflow tài liệu và không phải là giao diện công khai chuẩn của kho.

## Yêu cầu ✅

Trạng thái hiện tại của kho chỉ cần:

- `git` để clone và làm việc lịch sử/các nhánh nội bộ
- Một trình soạn thảo hỗ trợ Markdown hoặc môi trường xem GitHub

Giả định:

- Không yêu cầu toolchain Python/Node/Rust hay phụ thuộc model/runtime vào lúc này vì chưa có pipeline thực thi nào được cam kết.

## Cài đặt 🛠️

Clone và vào kho:

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

Môi trường chọn lọc cho chỉnh sửa:

```bash
git checkout -b docs/improve-onboarding
```

Nếu mục tiêu của bạn là cập nhật bản dịch, hãy chỉnh sửa cả `README.md` lẫn tệp `i18n/README.xx.md` tương ứng.

## Cách sử dụng ▶️

Hiện tại chưa có entrypoint thực thi, nên cách sử dụng đang tập trung cho tài liệu:

```bash
# Inspect repository contents
ls -la

# Read project overview
cat README.md
```

Khi các thành phần triển khai xuất hiện, phần này nên chuyển thành hướng dẫn chạy lệnh (dataset, model, train/infer).

## Cấu hình ⚙️

Hiện tại chưa có bề mặt cấu hình runtime.

Các khu vực cấu hình dự kiến (khi có mã):

- Đường dẫn gốc dataset
- Thư mục checkpoint và output
- Tham số tái tạo holographic
- Metadata cảm biến sự kiện và lựa chọn hiệu chỉnh
- Preset tái lập (seed, split, augmentations)

## Ví dụ 📌

Các ví dụ thực tế trong snapshot này là các lệnh khám phá kho:

```bash
# Confirm license header
head -n 5 LICENSE

# Verify language documentation coverage
ls -la i18n

# Read auto-generated context (optional)
ls -la .auto-readme-work
```

Nếu bạn đang mong đợi ví dụ huấn luyện/suy diễn, kho hiện tại chưa có chúng.

## Ghi chú phát triển 🧪

- Đây là một scaffold kho ở giai đoạn đầu với ưu tiên documentation-first.
- Giữ các tuyên bố kỹ thuật gắn chặt với tài sản đã được commit trong cây mã.
- Cập nhật README theo từng bước, duy trì bối cảnh lịch sử và tính nhất quán bản dịch.
- Nếu bạn thêm mã, hãy đặt chi tiết triển khai, đầu ra mong đợi và bước tái lập cùng tài liệu này.

## Khắc phục sự cố 🩺

### “Hiện chưa có gì để chạy"

Đây là điều đã dự kiến trong trạng thái hiện tại. Chưa có script, config, notebook hay dataset chạy được nào được commit.

### “Các README đã dịch ở đâu?”

Xem thư mục `i18n/`. Nếu thiếu ngôn ngữ mục tiêu, thêm `i18n/README.<lang>.md` và đồng bộ các liên kết điều hướng ngôn ngữ.

### “Tại sao tên tiêu đề lại khác nhau?”

Cụm từ trong ghi chú gốc là `Event-assited` (chỉ một chữ `s`), được giữ nguyên trong dòng legacy có trích dẫn. README này dùng chữ đúng `Event-assisted` trong nội dung mới.

### “Nên dùng thư mục `.auto-readme-work/` không?”

Xem đây là siêu dữ liệu sinh README đã tạo ra. Nó thường không cần thiết cho người đóng góp chuẩn, trừ khi họ làm tài liệu tự động.

## Lộ trình 🗺️

- Thêm metadata bài báo (liên kết công bố, DOI, và khối trích dẫn BibTeX)
- Thêm entrypoint triển khai và hướng dẫn sử dụng có thể tái lập khi có sẵn
- Bổ sung tài liệu dataset, tiền xử lý và cấu hình thí nghiệm
- Thêm mẫu issue/PR và tài liệu tự động hóa đóng góp
- Duy trì tính đồng bộ giữa các README đa ngôn ngữ và bản tiếng Anh

## Đóng góp 🤝

Đóng góp được hoan nghênh.

Cho đến khi có template chuyên dụng, dùng workflow chuẩn sau:

1. Fork repository
2. Tạo nhánh chuyên biệt (`docs/<topic>`)
3. Commit các thay đổi nhỏ, dễ review với thông điệp rõ ràng
4. Mở PR với lý do, danh sách file thay đổi chính xác, và lệnh xác minh nếu có

Nếu bạn thêm hướng dẫn kỹ thuật, hãy đưa ví dụ mức lệnh và đầu ra mong đợi kèm theo.

## Trích dẫn 📚

Chi tiết trích dẫn hiện chưa có trong repository.

Khi bài báo tương ứng được công bố, thêm một khối `BibTeX` và liên kết công bố vào phần này.

## Lời cảm ơn 🙏

Hiện chưa có lời cảm ơn nào được định nghĩa trong các tệp dự án.

Nếu có cơ quan, tổ chức hoặc cộng tác viên cần ghi nhận, hãy bổ sung trong lần cập nhật tiếp theo.

## Giấy phép 📄

Dự án này được cấp phép theo Apache License 2.0. Xem [LICENSE](./LICENSE).


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
