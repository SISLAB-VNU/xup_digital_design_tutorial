# Thiết kế điện tử số sử dụng Vivado IPI

Chương trình hỗ trợ đại học của Xilinx (XUP) đã phát triển [thư viện](./sources/XUP_LIB) các khối IP chức năng cơ bản có thể được dùng để tạo ra các thiết kế số bằng cách vẽ mạch điện (schematic). Các bài tập hướng dẫn (tutorial) và bài tập thực hành hướng đến các hàm lô-gic số (Digital Boolean) thực tế và bo mạch TUL PYNQ-Z2, tuy nhiên, chúng có thể được dùng với bất kỳ bo mạch nào được hỗ trợ bởi Chương trình hỗ trợ đại học của Xilinx (XUP). Tài liệu cho bài thực hành hướng đến việc sử dụng trong khóa học giới thiệu về Thiết kế Số trong đó giảng viên giới thiệu công nghệ FPGA trong khóa học để kiểm chứng các nguyên lý đã học qua việc tạo ra các thiết kế dùng Vivado.

Bài hướng dẫn được phát triển để người dùng (sinh viên) làm quen với quy trình thiết kế số trong các thiết bị khả trình của Xilinx sử dụng Bộ tích hợp IP (IPI) trong Vivado. Bài hướng dẫn "Cách tự tạo mới một khối IPI" hướng dẫn các bạn các bước để tạo tạo ra một khối IPI tùy chỉnh và sau đó sử dụng nó trong các thiết kế tiếp theo.

Trong bài thực hành này, chúng ta sẽ sử dụng Vivado phiên bản 2021.2 chạy trên windows 10.

## Tài liệu của các bo mạch được hỗ trợ

| Loại tài liệu                  | Link                                                         |
| ------------------------------ | ------------------------------------------------------------ |
| Tập tin Boolean Board Master XDC  | [Boolean.xdc](https://www.realdigital.org/downloads/8d5c167add28c014173edcf51db78bb9.txt) |
| Bản vẽ mạch Boolean        | [Schematic](https://www.realdigital.org/downloads/63f9a8205ebd9c2e8c2d265ad25097dc.pdf) |
| Tài liệu tham chiếu Boolean Board | [Reference Manual](https://www.realdigital.org/doc/02013cd17602c8af749f00561f88ae21) |
| Tập tin PYNQ-Z2 Master XDC     | [PYNQ-Z2 Master XDC](https://dpoauwgwqsy2x.cloudfront.net/Download/pynq-z2_v1.0.xdc.zip) |
| Bản vẽ mạch điện PYNQ-Z2       | [Schematics (PDF)](https://dpoauwgwqsy2x.cloudfront.net/Download/TUL_PYNQ_Schematic_R12.pdf) |
| Hướng dẫn sử dụng PYNQ-Z2      | [PYNQ-Z2 User Manual (PDF)](https://dpoauwgwqsy2x.cloudfront.net/Download/pynqz2_user_manual_v1_0.pdf) |
| XUP LIB                        | [Library Components List.pdf](https://www.xilinx.com/content/dam/xilinx/support/documentation/university/Vivado-Teaching/Digital-Design/2014x/docs-pdf/Library_Components_List.pdf) \| [Libarary File](./sources/XUP_LIB) |

## Tài liệu của các bài thực hành

| Tiêu đề                                         | Mã nguồn                                                   |
|-------------------------------------------------|----------------------------------------------------------|
| Hướng dẫn sử dụng thư viện XUP IPI trong Vivado | [sources](./sources/Vivado_Tutorial_Using_IP_Integrator) |
| Tự tạo mới một khối IPI                         | [sources](./sources/Vivado_Tutorial_Using_IP_Integrator) |

**Chú ý**: Bài hướng dẫn này đang được hoàn thiện.



------------------------------------------------------
<p align="center">Bản quyền&copy; 2022, Tập đoàn Advanced Micro Devices.</p>
