Virtual machine:  
  Команды:  
  1)set adr val - adr адрес ячейки в памяти, а val значение, помещаемое в адрес.  
  2)jsin adr - ввод в ячейку с адресом adr.  
  3)jsout adr - вывод в консоль переменной, лежащей в ячейке с адресмо adr.  
  4)add adr1 adr2 adr3 - сложение содержимого ячеек с адресами adr1 и adr2 и помещение результата в ячейку с адресом adr3.  
  5)mul adr1 adr2 adr3 - умножение содержимого ячеек с адресами adr1 и adr2 и помещение результата в ячейку с адресом adr3.  
  6)jmp adr - перенос ip на ячейку в памяти с адресом adr.  
  7)jscmd adr1 adr2 adr3 - операция аналогичная if(a < b), где адрес а = adr1, адрес b = adr2. По результату сравнения, если условие истинно, то порядок выполнения не изменяется, иначе ip переносится на ячейку памяти с адресом adr3.  
    
  Input:  
  node vm.js program.txt  
  program.txt - выполняемая программа.  
  
  Output:  
  В консоли. По завершении работы вывод "Finish";
