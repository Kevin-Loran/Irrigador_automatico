# Sistema de Irrigação Automática

## Sobre o projeto

Protótipo de um sistema de irrigação automática desenvolvido em 2024 para a disciplina de Modelagem e Simulação de Sistemas Elétricos e Magnéticos, no curso de Engenharia de Software da Universidade São Judas Tadeu.

O projeto utiliza um Arduino Uno, um sensor de umidade do solo e uma mini bomba d'água para automatizar o processo de irrigação de acordo com a umidade do solo.

O objetivo foi desenvolver uma solução de baixo custo para automatizar a irrigação e reduzir o desperdício de água.

## imagens do protótipo

<img width="579" height="438" alt="image" src="https://github.com/user-attachments/assets/e4636d13-ef95-45be-944b-cce0b81e21f7" />

<img width="572" height="436" alt="image" src="https://github.com/user-attachments/assets/78ea3665-619d-4d6e-b75c-59ad18274488" />



## Como funciona

O sistema utiliza um sensor de umidade conectado ao Arduino para verificar as condições do solo.


```text
Sensor de umidade
       |
       v
    Arduino
       |
       v
Verificação da umidade
       |
   +---+---+
   |       |
   v       v
Solo seco  Solo úmido
   |       |
   v       v
Aciona    Mantém
bomba     bomba desligada
   |
   v
Irrigação
```

diagrama: 
<img width="732" height="343" alt="image" src="https://github.com/user-attachments/assets/e5152051-fa4a-44fd-bc1c-5e45b037660a" />

