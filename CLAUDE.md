Làm việc trong repo **Docs-fork**.

Đọc kỹ toàn bộ `assessment-requirement/` trước, sau đó đọc `Definition-of-Done.md`.

**Nhiệm vụ hiện tại: kiểm tra và chỉnh DoD theo cấu trúc, workflow dưới đây.** Chưa đọc/sửa API contract, template hoặc tài liệu khác. Chưa tạo user stories hay tickets.

## Project

Mục tiêu **Ultimo + Ultra HD**:
- FE: Next.js / Headless.
- BE: Java / Microservices.
- PostgreSQL, Redis, Kafka, Docker.
- Bonus: Kubernetes.

## Cấu trúc công việc

**Epic → User Stories → Tickets**

Một Epic có một hoặc nhiều User Stories. Một User Story thông thường có các tickets:
- `[Docs]`: API contract/documentation cho story.
- `[UI/UX]`: thiết kế UI.
- `[BE] Build`: implement backend.
- `[FE] Build`: implement frontend.
- `Test Dev`: test trên branch `test`, checkout từ `dev`.
- `Production Readiness`: chuẩn bị materials, calendar và communication để release theo lịch đã hẹn với CP. Đến lịch thì lên production, merge `main`.

Mặc định BE và FE do cùng một người làm, nhưng vẫn là hai tickets riêng. Hai build tickets Done đồng nghĩa API tests, unit tests và integration tests ở local đã hoàn tất theo phạm vi liên quan.

## Level of Application

Chỉnh cột này theo quy ước:

- **Epic:** chỉ dùng tên `Epic`, không có hậu tố.
- **User Story:** có hậu tố thể hiện context, như `User Story - Design`, `User Story - Development`, `User Story - Testing`, `User Story - Documentation`, `User Story - Deployment`.
- **Team Integration - Internal**
- **Squad Integration - CP–PP**
- **Cross-squad Integration - PMS**

Thay các level `Issue - …` bằng `User Story - …`. Các context đang đặt dưới `Epic - …` cũng chuyển về `User Story - …`. Chỉ giữ tiêu chí hoàn tất tổng thể ở cấp `Epic`.

Đây là cách phân cấp trong **bảng DoD**, không phải yêu cầu bỏ các tickets bên trong User Story. Không lấy sáu loại ticket làm sáu level mới.

## Cách chỉnh DoD

Giữ bảng 5 cột hiện có:
`No. | Level of Application | Category | Definition of Done Details | Notes`

Đọc từng dòng và:
- Giữ tiêu chí còn đúng.
- Đặt tiêu chí vào đúng level/context.
- Chỉnh test, merge và release cho khớp workflow mới.
- Bỏ nội dung trùng hoặc lỗi thời.
- Không cắt mất nội dung cần thiết chỉ để rút ngắn.

Nội dung bằng tiếng Anh, ngắn gọn, rõ ràng, mỗi hàng kiểm tra được một điều kiện. Category được phép lặp lại.

Tách rõ test local, Test Dev, integration trong team, CP–PP và cross-squad/PMS. Không tự bổ sung branching strategy hoặc cam kết của CP khi chưa được xác định.

Chỉ tập trung vào công việc làm project: design, documentation, build, test, integration và release. Không đưa yêu cầu nộp M1/M2, contribution hoặc quản lý team vào bảng.

**Chỉ sửa `Definition-of-Done.md`.** Chỉnh trên nội dung hiện có, không tự thiết kế lại toàn bộ. Chỗ chưa rõ thì hỏi cụ thể, không tự điền giả định.

Sau khi sửa, báo ngắn gọn những nhóm đã đổi và lý do. Không commit hoặc push.