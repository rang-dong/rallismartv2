---
layout: page
title: Home
subtitle: Welcome to RalliSmart app
sitemap:
  priority: 0.9
---

<img src="{{ '/assets/img/pudhina.jpg' | prepend: site.baseurl }}" id="about-img">

# Ứng dụng Android

Dev: [https://install.appcenter.ms/.../.../.../fpt](https://install.appcenter.ms/users/tungpt46.fpt/apps/hirangdong-android/distribution_groups/fpt)

Staging: [https://install.appcenter.ms/.../.../.../fpt-staging](https://install.appcenter.ms/users/tungpt46.fpt/apps/hirangdong-android/
distribution_groups/fpt-staging)

Production: [https://install.appcenter.ms/.../.../.../fpt-production](https://install.appcenter.ms/users/tungpt46.fpt/apps/hirangdong-android/distribution_groups/fpt-production)

# Ứng dụng iOS

Testflight: [https://testflight.apple.com/join/0Zg2onVM](https://testflight.apple.com/join/0Zg2onVM)

---

# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.22] (152)

- Tạo Rule cho bảng cảnh AC
- Bảng cảnh Ralli mất màu nền (RD-SC06)
- Vẫn hiển thị trạng thái cũ khi quét lại thiết bị đã xóa
- Không hiện kết nối local khi bắt wifi nhà

## [1.2.20] (151)

### Fixed

- Thông báo
- Không đóng popup hướng dẫn khi cài wiffi
- Công tắc cơ hiện sai thời gian hoàn thành

## [1.2.19] (149)

- Thêm bản tin Connect to cloud
- Fixbug xoá cảnh
- Fixbug Xoá báo thức/ngủ
- Fixbug xoá nhầm HC

## [1.2.18] (148)

### Fixed

- Sửa lỗi session
- Sửa lỗi build sigr

## [1.2.17] (147)

### Fixed

- Công tắc cơ hiển thị sai số nút
- Công tắc cơ báo lỗi "Thiết bị đang ngoại tuyến"
- Không đồng bộ thiết bị đầu ra Rule
- Cài đặt Rule
- Sửa thông tin tài khoản bị crash

## [1.2.15] (145)

### Fixed

- Lỗi đổi tên thiết bị
- Thêm loading khi điều khiển thiết bị

## [1.2.13] (144)

### Fixed

- Lỗi đổi tên thiết bị

## [1.2.12] (143)

### Fixed

- Fix bug: cập nhật tên người dùng
- Hiển thị công tắc liên thông đã xóa
- Lỗi trường fade in
- Báo thức đi ngủ: sai trường thời gian
- Không sửa được rule
- Lỗi không đăng nhập

## [1.2.11] (142)

### Fixed

- Sửa luồng chia sẻ nhà theo api mới
- Fixbug đổi màu công tắc
- Sửa lỗi ổ cắm wifi
- Sửa lỗi tạo mới nhà
- Sửa lỗi không hiện đủ phòng, hiển thị sai thiết bị đầu ra khi

## [1.2.10] (141)

### Fixed

- Sửa luồng chia sẻ nhà

## [1.2.8] (139)

### Fixed

- Lỗi thêm thiết bị Tuya

## [1.2.8] (138)

### Fixed

- Sửa lỗi tính năng chia sẻ nhà

## [1.2.8] (137)

### Fixed

- Lỗi lặp thiết bị smart home ở trang chủ

## [1.2.8] (136)

### Changed

- Tạm thời bỏ check offline của công tắc

### Fixed

- Sửa lỗi điều khiển công tắc thiếu nút bấm

## [1.2.8] (135)

### Changed

- Sửa các lỗi không bấm được vào thiết bị điều khiển ở trang chủ

## [1.2.7] (132) - iOS Only - 2022-11-28

### Changed

- Sửa lỗi không đăng nhập vào ứng dụng được ở iOS <16 (loại bỏ log thông tin manufacturer)

## [1.2.6](129) - 2022-11-21

### Added

- Bổ sung các log theo dõi hệ thống về lỗi xóa tài khoản để theo dõi
- Bổ sung thông tin thiết bị phục vụ log và kiểm tra lỗi trên Cloud

### Changed

- Sử dụng In-app browser cho Rạng Đông Store

### Fixed

- Nâng cấp thư viện Tuya V4 (tránh lỗi crash trên Android 12)
- Nâng cấp thư viện Tuya V4 iOS
- Sửa lỗi đăng xuất bị trắng màn hình
- Tạm thời gỡ showroom 3D làm nhẹ ứng dụng để tối ưu thêm
- Sửa lỗi hiển thị phiên bản trong trang cập nhật

### Removed

- Tối ưu thao tác vuốt trượt màn hình Home trên Android

## [1.2.4](127) - 2022-11-21

### Added

### Changed

### Fixed

- Hotfix RGB
- Hiển thị tên người dùng

## [1.2.2](125) - 2022-11-19

### Added

- Dormitory Linking for Google and Maika

### Changed

### Fixed

## [1.1.8](96) - 2022-09-12

### Added

- Thêm thiết bị: Công tắc RGB, bảng cảnh RGB, công tắc cơ điện tử, cảm biến chuyển động AC.
- Công tắc liên thông.
- Thêm chức năng HCL
- Thêm chức năng thay thế HC.

### Changed

- Xác thực xoá HC
- Lọc danh sách nhà & phòng theo tên.

### Fixed

- Sửa lỗi cài đặt Rule.
- Sửa lỗi Tap-to-run.
- Sửa cài đặt tên theo nút.
- Sửa lỗi trạng thái HC.

## [1.1.6]() - 2022-08-07

### Added

- Thêm chức năng xóa tài khoản.
- Thêm thông báo khi điều khiển phòng, nhóm thiết bị có tất cả thiết bị offline.
- Thêm chức năng sao lưu, khôi phục HC.
- Thêm cài đặt thông báo cho cảm biến cửa.
- Thêm cài đặt công tắc rèm trong Rule.
- Thêm chức năng TapToRun.

### Changed

- Sửa giao diện đăng nhập qua mạng xã hội.
- Sửa lỗi cài đặt công tắc đèn.
- Chuyển luồng điều khiển Tuya sang C2C.

### Fixed

- Sửa lỗi cài đặt tên nút của công tắc.
- Sửa lỗi phân quyền tài khoản.
- Sửa giao diện điều khiển Tuya.
- Sửa lỗi cài đặt rule cho công tắc ACDC.
- Sửa thông tin ở màn hình danh sách Rule.

## [1.1.5]() - 2022-07-09

### Added

- Thêm loại thiết bị IR hỗ trợ.
- Thêm chức năng cài đặt tên cho nút bấm của công tắc.

### Changed

- Cập nhật thay đổi cài đặt Rule.
- Cập nhật giao diện Switch on-off.
- Cập nhật giao diện thời gian giữ chuyển động cho cảm biến ánh sáng chuyển động.

### Fixed

- Sửa lỗi đăng ký với tài khoản đã đăng ký.
- Sửa lỗi phần quyền chủ nhà thành member.
- Sửa lỗi cập nhật tên nhà thành rỗng.
- Sửa lỗi đồng bộ dữ liệu.

## [1.1.4]() - 2022-06-25

### Added

- Thêm công tắc đèn vào phòng smartlighting.
- Thêm giao diện hiển thị pin cho DKTX M4.
- Xử lý trạng thái on off của thiết bị Wifi.

### Changed

- Thay đổi cài đặt thành 6 cảnh mặc định.
- Cấu hình thời gian kết nối SignalR.
- Ẩn lựa chọn thiết bị Tuya trong Rule.
- Ẩn giao diện HCL.
- Thay đổi luồng gửi RefreshToken cho HC.

### Fixed

- Sửa lỗi HC connect với Cloud.
- Sửa lỗi cài đặt khoảng thời gian khi thiết lập cảnh cho cảm biến ánh sáng chuyển động.
- Sửa lỗi thêm thành viên vào nhà.
- Sửa lỗi đếm số lượng thiết bị trong màn hình quét thiết bị.
- Sửa lỗi xử lý phản hồi thiết bị.
- Sửa lỗi thêm, xóa thiết bị trong phòng.
- Sửa lỗi phần quản lý thiết bị con của IR.
- Sửa lỗi gửi thừa bản tin cài đặt cảm biến bụi mịn khi cài đặt Rule.
- Sửa lỗi điều khiển phòng, nhóm có công tắc đèn.
- Sửa giao diện cài đặt Rule.
- Sửa lỗi dữ liệu khi đăng xuất.
- Sửa lỗi chuyển nhà bị treo app.
- Sửa lỗi gửi sai báo thức, báo ngủ khi xóa phòng.
- Sửa lỗi đồng bộ trạng thái khi điều khiển thiết bị.
- Sửa lỗi countdown thiết bị Tuya.
- Sửa lỗi treo app khi xóa phòng
- Sửa lỗi đồng bộ trạng thái thiết bị.
- Sửa bản tin cài đặt Khác trong automation.
- Sửa lỗi thêm HC vào nhà.
- Sửa phản hồi thiết bị Tuya.
- Sửa icon công tắc rèm và truy cập màn hình chi tiết từ màn hình chính.
- Sửa lỗi xóa nhà.
- Sửa lỗi đồng bộ dữ liệu.

## [1.1.3]() - 2022-05-28

### Added

- Thêm tùy chọn Rule với các điều kiện đầu vào.
- Hỗ trợ thiết bị rèm cửa thông minh.

### Fixed

- Sửa lỗi cuộn màn hình trên giao diện thông tin thiết bị thông minh.
- Sửa lỗi cấp quyền sử dụng vị trí.
- Sửa lỗi đồng bộ Tuya.
- Sửa lỗi hiển thị trạng thái HC.
- Sửa lỗi điều khiển đèn qua cloud.
- Sửa lỗi reconnect signalr.
- Sửa lỗi gửi thiếu bản tin kết nối HC qua Cloud.

## [1.1.2]() - 2022-05-10

### Fixed

- Sửa lỗi cài đặt cảm biến ánh sáng chuyển động cho Rule.
- Sửa lỗi cài đặt cảm biến bụi mịn cho Rule.
- Sửa lỗi xác thực người dùng Tuya.

## [1.1.1]() - 2022-05-06

### Changed

- Thay đổi cách tính DIM của phòng, nhóm thiết bị.
- Thay đổi luồng đồng bộ cảnh.

### Fixed

- Sửa trạng thái kết nối HC.
- Cập nhật luồng đồng bộ trạng thái thiết bị.
- Sửa lỗi chuyển nhà.
- Sửa lỗi tạo cảnh iOS.
- Sửa lỗi thêm mới thiết bị.
- Sửa lỗi mất màu tên nhà.
- Sửa lỗi tạo Rule có nhiều cảnh nối tiếp giống nhau.

## [1.1.0]() - 2022-04-25

### Added

- Thêm các thiết bị Tuya: Ổ cắm thông minh, Điều khiển hồng ngoại IR.
- Thêm tính năng tạo nhóm thủ công.
- Thêm tính năng tạo cảnh thủ công có độ trễ.
- Thêm tính năng tạo cảnh đầu ra nối tiếp trong Rule.

### Changed

- Thay đổi luồng trạng thái on/off thiết bị.

### Fixed

- Sửa lỗi đồng bộ trạng thái thiết bị.

## [1.0.47]() - 2022-04-22

### Added

- Thêm các thiết bị Tuya: Ổ cắm thông minh, Điều khiển hồng ngoại IR.
- Thêm tính năng tạo nhóm thủ công.
- Thêm tính năng tạo cảnh thủ công có độ trễ.
- Thêm tính năng tạo cảnh đầu ra nối tiếp trong Rule.

### Changed

- Thay đổi luồng trạng thái on/off thiết bị.

### Fixed

- Sửa lỗi đồng bộ trạng thái thiết bị.

## [1.0.46]() - 2022-03-14

### Changed

- Sửa lỗi đồng bộ dữ liệu phòng.
- Sửa thông tin trạng thái thiết bị.
- Sửa trạng thái on/off thiết bị.
- Sửa lỗi cảnh mặc định đèn Downlight màu
- Thêm đèn Led dây RGB.

## [1.0.45]() - 2022-02-12

### Changed

- Sửa định dạng thời gian ở bản tin.
- Sửa lỗi đồng bộ dữ liệu.
- Sửa lỗi đồng bộ trạng thái thiết bị.

## [1.0.44]() - 2022-01-27

### Changed

- Sữa lỗi phân quyền chọn ảnh cho cảnh.
- Cập nhật device unicast qua bản tin phản hồi.
- Thêm tính năng Đồng bộ tất cả.
- Sửa lỗi đồng bộ thiết bị
- Sửa lỗi danh sách nhà.
- Sửa lỗi tên của thiết bị mới.

## [1.0.43]() - 2022-01-13

### Changed

- Yêu cầu xóa nếu quét được thiết bị đã tồn tại.

## [1.0.42]() - 2022-01-11

### Changed

- Tối ưu đồng bộ thiết bị.
- Bỏ thời gian chờ sửa cảnh.
- Sửa giao diện ánh sáng chuyển động.
- Sửa thanh kéo cài đặt Tự động.
- Sửa bản tin tạo cảnh, thêm thiết bị vào phòng, cài đặt cảnh cho màn hình.

### Fixed

- Sửa lỗi Bảng cảnh trong cài đặt Tự động.
- Sửa lỗi xóa thành viên khỏi nhà.
- Sửa lỗi cập nhật thông tin người dùng.
- Sửa lỗi đồng bộ trạng thái thiết bị.

## [1.0.41]() - 2021-12-23

### Fixed

- Thay đổi giao diện ánh sáng chuyển động.
- Sửa lỗi đồng bộ ảnh của cảnh.

## [1.0.40]() - 2021-12-19

### Fixed

- Trạng thái lỗi khi lấy danh sách nhà.
- Đổi hiển thị địa chỉ nhà thành tên nhà.
- Cập nhật trạng thái thiết bị, trạng thái HC, icon trạng thái HC.
- Bỏ timeout chọn cảnh, cache image scene.
- Sửa lỗi xóa thiết bị có cài đặt cảnh.

## [1.0.39]() - 2021-12-11

### Added

- Bổ sung bảng cảnh M3.
  = Bô sung hiển thị pin cho công tắc cảnh cầm tay.

### Fixed

- Lỗi kết nối wifi có SSID tiếng việt.

## [1.0.38]() - 2021-12-08

### Changed

- Sửa lỗi giao diện thanh điều khiển DIM.
- Sửa đồng bộ trạng thái cảm biến nhiệt độ, độ ẩm.
- Thêm đăng xuất cho màn hình danh sách nhà.

## [1.0.37]() - 2021-12-04

### Added

- Bổ suing activity log
- Bổ sung phiên bản của thiết bị

### Changed

- Tách cảnh cho cảm biến chuyển động

### Fixed

- Cập nhật thông tin người dùng
- Lỗi đồng bộ HC

## [1.0.34]() - 2021-11-27

### Changed

- Sửa lỗi giao diện danh sách.
- Sửa đồng bộ HC.
- Sửa sửa lỗi công tắc 4 nút.

## [1.0.33]() - 2021-11-26

### Changed

- Thay đổi icon phòng, thiết bị.
- Sửa một số lỗi giao diện.
- Sửa điều khiển nhóm đèn.

## [1.0.32]() - 2021-11-24

### Changed

- Fix một số bug điều khiển.
- Fix một số bug giao diện.
- Xóa scene đã chọn cho bảng cảnh,...

## [1.0.30]() - 2021-11-17

### Changed

- Displayname
- Validate password đăng ký tài khoản
- Update version HC khi scan

## [1.0.29]() - 2021-11-16

### Fixed

- Fix bug đồng bộ rule, v.v...
- Fix một số bug giao diện.
- Fix thêm lại thiết bị lỗi khi tạo scene.

## [1.0.28]() - 2021-11-13

### Changed

- Icon app
- Đổi cảnh mặc định cho scene

### Fixed

- Fix bug đồng bộ trạng thái cảm biến, v.v...
- Fix bug crash khi đổi wifi

## [1.0.27]() - 2021-11-10

### Added

- Mã hoá mật khẩu HC

### Changed

- Đổi tên thiết bị, scene mặc định

### Fixed

- Fix bug sync scene, alarm, sleep, v.v...

## [1.0.23]() - 2021-10-12

### Added

- Add code push.
- Add the feature to config sensor device.

### Fixed

- Fix sync scene, alarm, sleep, v.v...
- Fix something up.

## [1.0.22]() - 2021-10-01

### Added

- Add the feature to signup by facebook.
- Add the feature to config HCL Rule...

### Fixed

- Fix bug notification.
- Fix sync scene, alarm, sleep, v.v...
- Fix something up.

## [1.0.21]() - 2021-09-21

### Fixed

- Fix crash app while create scene.
- Fix bug create scene.
- Fix something up.

## [1.0.19]() - 2021-09-16

### Added

- Add the feature to signup by phone.
- Add the feature to config device with the phone uniqueId...

### Changed

- Update UI Android, IOS...
- Remove unused files.

### Fixed

- Fix scene when selected.
- Fix crash app while controlling the device.
- Fix sync scene, member, dormitory, home controller, attribute value, v.v...
- Fix something up.

## [1.0.16]() - 2021-08-24

### Added

- Add the feature to edit the device name.
- Add the feature to update profile.
- Add switchScreen in AutoScreen.tsx.

### Fixed

- Fix Wi-Fi name encoding.
- Fix navigation when deleting dormitory.
- Fix require pwd when connecting HC.
- Fix sync home controller, dormitory, room, v.v... 
