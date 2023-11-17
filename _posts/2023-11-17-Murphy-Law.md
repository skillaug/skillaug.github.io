---
layout: post
title: Định luật Murphy và Những Bài Học Cho Lập Trình Viên
---
Định luật Murphy là một quy luật không chính thức nhưng lại rất phổ biến trong cuộc sống và công việc, đặc biệt là trong ngành phát triển phần mềm. Định luật Murphy phát biều rằng: "Bất cứ điều gì có thể sai sẽ xảy ra và vào thời điểm tồi tệ nhất có thể". Đại loại là nếu có khả năng xảy ra một sự cố hoặc một lỗi nào đó, thì nó sẽ xảy ra, và thường thì đưa code lên production thì nó mới lỗi.

Khi thiết kế và xây dựng hệ thống phần mềm, từ những dòng code nhỏ nhất, điều quan trọng là phải nghĩ đến tất cả các nguyên nhân có thể xảy ra lỗi của hệ thống, hạn chế hoặc thậm chí đừng nghĩ đến "happy path", quên đi cũng được, vì nó quá hiển nhiên và là điều cần phải hoàn thành. Đừng quá tin vào input đầu vào được cung cấp bởi client, họ có thể có sai sót do hiểu sai vấn đề. Quan trọng nữa, hãy cẩn thận, có thể người gửi input lên cho bạn không phải người "tốt".

Đừng quên: Bất cứ điều gì có thể sai sẽ xảy ra và vào thời điểm tồi tệ nhất có thể.
