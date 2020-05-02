# Biblioteca Registry-Generator

A biblioteca Registry-Generator gera automaticamente registros, levando como parâmetros iniciais: ano atual + semestre, para o cadastro de pessoas e/ou produtos no Android Studio.

## Instalação

Em breve.

## Uso

Com a biblioteca instalada e configurada, deve-se ser instanciada sua classe ```MatriculaGenerator```, esta que fará uso de sua função ```registry``` que solicitará um parâmetro do tipo String a fim de limitar a criação randômica dos digitos para seu registro (lembrando que o** registro será iniciado com o ano e semestre atuais**, caso seu parâmetro seja ```"3"```, a função te retornará um registro de 8 digitos).
```
MatriculaGenerator matriculaGenerator = new MatriculaGenerator(); 
String registry = matriculaGenerator.registry("5");
```

## Créditos
- Desenvolvedor: [Vitória Camila](https://github.com/itsvickie "Vitória Camila")
- Contribuintes: [Gabriel Almeida](https://github.com/Sprained "Gabriel Almeida")



## Licença

```
MIT License

Copyright (c) 2020 Shreyas Patil

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
