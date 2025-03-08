Para compilar o projeto:
   ```sh
   gcc -o assembler main.c lexer.c parser.c -Wall
   
   ```
   
Uso:
   ```sh
   ./assembler {arquivo de entrada} {arquivo de saida}
   ```

Exemplo:
   ```sh
   ./assembler codigo_teste.txt resultado.mem
   ```
