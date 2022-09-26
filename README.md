![enter image description here](https://i.ytimg.com/vi/ULtNZ8uXcMU/maxresdefault.jpg)
# [RPA Challenger] IBM RPA (WDG) com JavaScript
## 💻 Projeto
Challenger de Robotic Process Automation afim de desenvolver habilidades com a ferramenta IBM RPA enfrentando dificuldades, mais dados sobre o challenger: [Clique aqui.](https://rpachallenge.com/)

### 📄 Solução aplicada para obter menos tempo de execução
Afim de utilizar um menor tempo para esse challenger foi utilizado javaScript e não funções nativas da aplicação, presando pela velocidade de execução.

    document.querySelector("[ng-reflect-name='labelFirstName']").value =  '${txNome}';
    document.querySelector("[ng-reflect-name='labelLastName']").value =  '${txSobrenome}';
    document.querySelector("[ng-reflect-name='labelCompanyName']").value =  '${txEmpresa}';
    document.querySelector("[ng-reflect-name='labelRole']").value =  '${txCargo}';
    document.querySelector("[ng-reflect-name='labelAddress']").value =  '${txEndereco}';
    document.querySelector("[ng-reflect-name='labelEmail']").value =  '${txEmail}';
    document.querySelector("[ng-reflect-name='labelPhone']").value =  '${txNumero}';
    document.querySelector("[value='Submit']").click();

### 🚀 Resultado final
![enter image description here](https://i.imgur.com/UXaQXV2.jpg)
