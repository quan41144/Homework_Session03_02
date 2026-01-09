# Homework_Session03_02
Nhận diện và mô tả các mối quan hệ giữa thực thể
# Mô tả các kiểu liên kết (1-1, 1-N, N-N) và ý nghĩa thực tế có trong sơ đồ ERD trên:
Mối quan hệ của thực thể Students và Class_Section là mối quan hệ N-N qua bảng trung gian là Enrollments, tách thành 2 mối quan hệ 1-N, với Students-Enrollments (1-N) và Class_section-Enrollments (1-N). (Vì một sinh viên có thể đăng ký nhiều lớp học phần, một lớp học phần có thể được đăng ký bởi nhiều sinh viên)
Mối quan hệ của Instructors và Class_section là mối quan hệ 1-N. (Vì một giảng viên có thể đăng ký dạy nhiều lớp học phần)
Mối quan hệ của Courses và Class_section là mối quan hệ 1-N. (Vì một môn học có thể được dạy trong nhiều lớp học phần)
Mối quan hệ của Instructors và Courses là mối quan hệ N-N qua bảng trung gian là Instructor_Courses, tách thành 2 mối quan hệ 1-N, với Instructors-Instructor_Courses (1-N) và Courses-Instructor_Courses (1-N). (Vì một giảng viên có thể dạy được nhiều môn học, một môn học có thể được dạy bởi nhiều giảng viên)
