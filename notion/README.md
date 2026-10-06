# NOTION WORKFLOW – PRODUCTIVITY WORKFLOW

## 1. Tổng quan sản phẩm

**Tên sản phẩm:** Notion Workflow

**Loại sản phẩm:** Phần mềm quản lý công việc và quy trình làm việc nhóm.

**Đối tượng sử dụng:**
- Sinh viên
- Nhóm làm bài tập lớn
- Nhóm dự án nhỏ
- Cá nhân cần quản lý công việc

> **Mục tiêu:** Xây dựng một hệ thống giúp người dùng tạo Workspace, quản lý Project, phân công Task, theo dõi Deadline và kiểm soát tiến độ công việc.

---

## 2. Vấn đề cần giải quyết

Trong quá trình làm việc nhóm thường xuất hiện các vấn đề:

- Công việc phân công chưa rõ ràng.
- Thành viên không biết mình cần làm gì.
- Khó biết ai đang thực hiện nhiệm vụ nào.
- Deadline dễ bị quên.
- Trưởng nhóm khó theo dõi tiến độ.
- Tài liệu và công việc nằm ở nhiều nền tảng khác nhau.
- Không xác định được công việc nào cần ưu tiên.

---

## 3. Giải pháp

Notion Workflow cung cấp một Workspace chung cho nhóm.

Trong Workspace, người dùng có thể:

- Tạo Project.
- Tạo Task.
- Phân công nhiệm vụ.
- Thiết lập Deadline.
- Thiết lập mức độ ưu tiên.
- Theo dõi trạng thái công việc.
- Trao đổi thông qua Comment.
- Theo dõi tiến độ thông qua Dashboard.
- Quản lý Task bằng Kanban Board.

---

# 4. Cấu trúc hệ thống

## Workspace

Một Workspace đại diện cho không gian làm việc của một nhóm.

Ví dụ:

**Workspace:** Nhóm 6 – Công nghệ phần mềm

### Project trong Workspace

- Notion Workflow
- Báo cáo Công nghệ phần mềm
- Presentation
- Testing

---

# 5. Project

Mỗi Workspace có thể có nhiều Project.

## Thông tin Project

- **Project Name:** Notion Workflow
- **Description:** Xây dựng phần mềm quản lý workflow cho nhóm.
- **Start Date:** 01/10/2026
- **Deadline:** 30/10/2026
- **Status:** In Progress
- **Progress:** 65%

---

# 6. Task Management

Mỗi Project được chia thành nhiều Task.

## Thuộc tính của Task

| Thuộc tính | Mô tả |
|---|---|
| Task Name | Tên nhiệm vụ |
| Description | Nội dung nhiệm vụ |
| Assignee | Người thực hiện |
| Status | Trạng thái |
| Priority | Mức độ ưu tiên |
| Start Date | Ngày bắt đầu |
| Deadline | Hạn hoàn thành |
| Project | Project chứa Task |

---

## Ví dụ Task

### Design Dashboard

**Assignee:** Nguyễn Minh Đức

**Status:** In Progress

**Priority:** High

**Deadline:** 15/10/2026

**Description:**

Thiết kế giao diện Dashboard cho hệ thống.

### Checklist

- [x] Thiết kế Sidebar
- [x] Thiết kế Header
- [ ] Thiết kế Project Card
- [ ] Thiết kế Task Overview
- [ ] Responsive giao diện

---

# 7. Workflow

Task được quản lý theo luồng:

**To Do → In Progress → Review → Done**

## Ý nghĩa trạng thái

### To Do

Task đã được tạo nhưng chưa bắt đầu.

### In Progress

Task đang được thành viên thực hiện.

### Review

Task đã hoàn thành bước thực hiện và đang được kiểm tra.

### Done

Task đã hoàn thành.

---

# 8. Kanban Board

## TO DO

- Thiết kế Database
- Statistics Page
- Notification

## IN PROGRESS

- Dashboard
- Task Page
- Backend API

## REVIEW

- Login Page
- Register Page

## DONE

- Requirement Analysis
- Product Vision
- User Persona

---

# 9. Mức độ ưu tiên

Task được chia thành 4 mức:

🔴 **Urgent** – Cần thực hiện ngay

🟠 **High** – Quan trọng

🟡 **Medium** – Bình thường

🟢 **Low** – Có thể thực hiện sau

---

# 10. Dashboard

Dashboard cung cấp thông tin tổng quan về Project.

## Tổng quan

| Chỉ số | Giá trị |
|---|---:|
| Total Tasks | 20 |
| Completed | 12 |
| In Progress | 5 |
| Overdue | 3 |

## Project Progress

**█████████████░░░░░ 65%**

---

# 11. Upcoming Tasks

### Design Dashboard

📅 Deadline: 15/10/2026  
🔴 Priority: High  
🟡 Status: In Progress

### Create Database

📅 Deadline: 17/10/2026  
🟠 Priority: High  
⚪ Status: To Do

### Write Report

📅 Deadline: 20/10/2026  
🟡 Priority: Medium  
⚪ Status: To Do

---

# 12. Calendar

Calendar hiển thị Deadline của các Task và Project.

### 15/10

- Design Dashboard

### 17/10

- Create Database

### 20/10

- Write Report

### 30/10

- Project Deadline

---

# 13. Team Members

| Thành viên | Vai trò | Công việc |
|---|---|---|
| Member 1 | Leader | Quản lý Project |
| Member 2 | Frontend | UI / UX |
| Member 3 | Backend | API |
| Member 4 | Database | Database |

---

# 14. Activity Log

### Recent Activity

**Nguyễn Minh Đức**
- Chuyển `Design Dashboard`
- `To Do → In Progress`

**Member 2**
- Tạo Task `Create Database`

**Member 3**
- Hoàn thành `Login Page`

---

# 15. Documents

Tài liệu của Project được lưu tập trung.

## Project Documents

- Requirement Analysis
- Product Vision
- User Persona
- User Story
- Use Case
- Database Design
- API Documentation
- Testing Documentation

---

# 16. Comment

Thành viên có thể trao đổi trong từng Task.

> **Leader:** Hoàn thành Dashboard trước ngày 15/10 nhé.

> **Frontend:** OK, mình đang làm phần Task Overview.

> **Leader:** Sau khi hoàn thành chuyển sang Review.

---

# 17. Luồng hoạt động

**User**

↓

**Login**

↓

**Workspace**

↓

**Project**

↓

**Task**

↓

**Assign Member**

↓

**Set Priority + Deadline**

↓

**To Do**

↓

**In Progress**

↓

**Review**

↓

**Done**

↓

**Project Progress**

---

# 18. Chức năng chính

- [x] Login / Register
- [x] Workspace
- [x] Project Management
- [x] Task Management
- [x] Assign Member
- [x] Priority
- [x] Deadline
- [x] Kanban Board
- [x] Dashboard
- [ ] Calendar
- [ ] Comment
- [ ] Statistics
- [ ] Notification
- [ ] Activity Log

---

# 19. MVP

## Version 1.0

Các chức năng bắt buộc:

- Login / Register
- Workspace
- Project
- Task
- Assign Task
- Priority
- Deadline
- Kanban
- Dashboard

## Version 2.0

Phát triển thêm:

- Calendar
- Comment
- Statistics
- Activity Log
- Notification
- Document Management

---

# 20. Điểm khác biệt với Notion

Notion là một nền tảng Workspace tổng quát cho phép người dùng tùy biến rất sâu.

**Notion Workflow tập trung vào quản lý quy trình công việc.**

Sản phẩm tập trung vào:

**Project + Task + Workflow + Team + Deadline + Progress**

Thay vì xây dựng một bản sao của Notion, sản phẩm hướng tới một hệ thống đơn giản hơn dành cho **sinh viên và nhóm dự án nhỏ**.

---

# 21. Product Vision

> **For:** Sinh viên và nhóm làm việc nhỏ  
>
> **Who:** Cần quản lý nhiều công việc và nhiệm vụ  
>
> **The:** Notion Workflow  
>
> **Is a:** Workflow Management Platform  
>
> **That:** Giúp quản lý Project, Task, Deadline và tiến độ  
>
> **Unlike:** Các ứng dụng ghi chú hoặc quản lý công việc đơn lẻ  
>
> **Our Product:** Tập trung vào quản lý quy trình làm việc nhóm trong một Workspace đơn giản và trực quan.

---

# 22. Tổng kết

**Notion Workflow** là một hệ thống quản lý công việc và quy trình làm việc nhóm.

Luồng chính của sản phẩm:

**Workspace → Project → Task → Workflow → Progress**

Sản phẩm giúp nhóm:

- Phân công công việc rõ ràng.
- Theo dõi Deadline.
- Biết trạng thái từng Task.
- Theo dõi tiến độ Project.
- Tăng khả năng phối hợp giữa các thành viên.
