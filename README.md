# Atividade - Formulários dinâmicos com Angular
## Semana 3 - Módulo 9 - Programação
### Livia Coutinho - Turma 3 - Engenharia de Software

## Introdução
Relatório para registro dos conceitos e práticas aprendidos durante a atividade de construção de formulários dinâmicos utilizando o framework Angular. O tutorial fornecido como base (https://angular.io/guide/dynamic-form) abrange conceitos e práticas para criar formulários dinâmicos baseados em metadados, permitindo a geração automática de diferentes versões de formulários com base em mudanças no modelo de dados.

## Tecnologia e conceitos aprendidos
Angular é um framework para construção de aplicações web, fornecendo uma estrutura robusta para desenvolver aplicativos de página única (SPA). Os principais conceitos aprendidos incluem:

**1. Reactive Forms:** os formulários dinâmicos são baseados em reactive forms, um recurso do Angular para lidar com formulários complexos e reativos.

**2. Modelo de objeto de formulário:** criação de um modelo de objeto que descreva os controles do formulário. Este modelo é usado para gerar automaticamente os formulários com base em metadados.

**3. Serviços:** foram utilizados serviços para fornecer dados e funcionalidades essenciais para a construção dos formulários dinâmicos. O QuestionService foi responsável por fornecer um conjunto de perguntas, enquanto o QuestionControlService ajudou na criação dos grupos de controle do formulário.

**4. Componentes e diretivas do Angular:** Componentes como DynamicFormComponent e DynamicFormQuestionComponent foram criados para representar o formulário dinâmico e suas questões. Diretivas como formGroup e formControlName foram utilizadas para conectar o HTML do template ao modelo de dados subjacente.

**5. Validação de entrada:** a validação de entrada de usuário, garantindo que o formulário só seja submetido quando estiver em um estado válido.

## Conclusão

A construção de formulários dinâmicos com Angular é importante para o desenvolvimento de aplicações web interativas e adaptáveis. O tutorial proporcionou uma compreensão dos conceitos fundamentais e práticas necessárias para criar formulários dinâmicos. Este conhecimento pode ser aplicado em uma variedade de cenários, desde questionários online até formulários de inscrição e pesquisa.

# Prints

Aplicação dos comandos:
- npm install -g @angular/cli
- ng new nome-do-projeto


• Inicialização do projeto Angular </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/1eefb256-63f3-463e-8560-6916c96a58f4)
</br>
• dynamic-form.component.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/484cf8fe-3ba5-42cf-9308-cffc56d336f3)
</br>
• dynamic-form-question.component.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/8644d2ad-ad79-4859-be09-b207dac06fc5)
</br>
• question-base.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/6010b5ab-b4d1-4235-8a35-e0d872764e06)
</br>
• question-textbox.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/0b98ddff-c7c5-48b8-ade1-d477cd296822)
</br>
• question-dropdown.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/5b8c429e-ace8-4a56-bb63-84a25793243b)
</br>
• question-control.service.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/c30b6d51-e8c2-4d52-9a34-561adf9591ce)
</br>
• dynamic-form.component.html </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/b7a00f98-68cb-4f3b-8c54-0531695cdae6)
</br>
• mudanças em dynamic-form.component.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/7da3715f-582b-4265-ab59-cfa062b9fc00)
</br>
• question.service.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/aef92d76-aecf-405f-acbf-0600bac80e27)
</br>
• app.component.ts </br>
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/69a29e6c-beb9-4307-8351-e09cdc50a9fb)
</br>
</br>
</br>
</br>
- Hora de rodar o código
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/01d1271b-cd99-4f17-83b1-a5e056ec676e)
![image](https://github.com/Livia-Coutinho/M9S4-Ponderada-LCoutinho/assets/99189965/a3c4cc17-d40f-400a-a075-2b469b4f6a08)


