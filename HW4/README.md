# Digital System Design：HW4

- 題目 1：[用 4 bits 加減法器組成 10 bits 加減法器](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/tree/main/HW4#題目-1用-4-bits-加減法器組成-10-bits-加減法器)
- 題目 2：[用 4 bits BCD 可串接上數器組成 3 位數 BCD 可串接上數器](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/tree/main/HW4#題目-2用-4-bits-bcd-可串接上數器組成-3-位數-bcd-可串接上數器)
- [License：MIT](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/tree/main/HW4#licensemit)

## 題目 1：[用 4 bits 加減法器組成 10 bits 加減法器](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/tree/main/HW4/adder_subtractor_10bits)

### 說明

- 輸入 Input：X、Y、MODE、Cin
- 輸出 Output：Cout、S

### 模擬測試波形圖

<img src="https://github.com/5j54d93/NTOU-CS-Digital-System-Design/blob/main/HW4/.guthub/assets/HW4-1.png" width='100%' height='100%'/>

## 題目 2：[用 4 bits BCD 可串接上數器組成 3 位數 BCD 可串接上數器](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/tree/main/HW4/cascade_BCD_upcounter_3digits)

### 說明

- 輸入 Input：CLK、RESET、CASIN
- 輸出 Output：CASOUT、F

`CASIN = 0` 時，前面沒進位，不能數。  
`CASIN = 1` 時，前面有進位，可以數。  
`CASOUT = 0` 時，自己還沒數滿，不用沒進位給下一位，下一個不能數。  
`CASOUT = 1` 時，自己數滿了，要進位給下一位，下一個可以數。

### 模擬測試波形圖

<img src="https://github.com/5j54d93/NTOU-CS-Digital-System-Design/blob/main/HW4/.guthub/assets/HW4-2.png" width='100%' height='100%'/>

## License：MIT

This package is [MIT licensed](https://github.com/5j54d93/NTOU-CS-Digital-System-Design/blob/main/LICENSE).
