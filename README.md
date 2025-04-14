<picture>
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fdchwr1s3cywfo5yaul0e.png">
</picture>

<br>

# DIO | Resumos Git e GitHub
Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)  
- [Documentação GitHub](https://docs.github.com/pt)

## ✍🏻 Resumos das Aulas
<details>
<summary><strong>O QUE É VERSIONAMENTO DE CÓDIGO</strong></summary>
<br>

Versionamento de código, também conhecido como controle de versão, é o processo de registrar e gerenciar as alterações feitas em um código.

|                 |                                                                                          |
| --------------- | ---------------------------------------------------------------------------------------- | 
| O que é         | Prática de acompanhar e gerenciar as alterações em um código                             | 
| Para que serve  | Gerenciar as alterações no código-fonte de um projeto                                    | 
| Quem usa        | Desenvolvedores que trabalham em equipe                                                  |
| Como funciona   | Utiliza repositórios locais e remotos para armazenar as versões do código                |
| Vantagens       | Permite trabalhar em equipe, reverter a versões anteriores, testar novas funcionalidades |
</details>

<details>
<summary><strong>CONFIGURANDO O GIT</strong></summary>
<br>Antes de começar a usar o Git, é essencial configurar seu nome e e-mail. Essas informações identificam suas alterações em projetos versionados.  
<br><br>

<strong>✔️ Passo a Passo para configurar o Git:

1. Abra o Git Bash </strong>
    - No Área de Trabalho, clique com o botão direito na tela e selecione <em>"Git Bash here"</em>.

2. <strong>Configure seu nome</strong>
    ```bash
    git config --global user.name "Seu Nome"
    ```
    <em>(Substitua `"Seu Nome"` pelo seu nome real ou usuário)</em>

3. <strong>Configure seu e-mail</strong>
    ```bash
    git config --global user.email "seu@email.com"
    ```
    <em>(Use o mesmo e-mail vinculado ao GitHub, se aplicável)</em>

4. <strong>Verifique as configurações</strong>
    ```bash
    git config --global --list
    ```
    <em>(Confira se `user.name` e `user.email` estão corretos)</em>
<br><br>

<strong>💡Observação Final:</strong>
Essas configurações são globais e aplicam-se a todos os projetos no seu computador. Para alterá-las, repita os comandos com os novos dados.
</details>

<details>
<summary><strong>CRIANDO E CLONANDO REPOSITÓRIOS LOCAIS/REMOTOS</summary></strong>
<br>Para trabalhar com Git, você pode criar um repositório local do zero e conectá-lo a um remoto (GitHub) ou clonar um repositório existente. Vamos ver ambos os métodos!
<br><br>

<strong>✔️ Passo a Passo para Criar um Repositório Local e Conectá-lo ao Repositório Remoto:  
1. Abra o Git Bash</strong>
    - Execute o Git Bash na pasta onde deseja criar o repositório local

2. <strong>Crie uma pasta para o projeto</strong>
    ```bash
    mkdir repositorio-local
    cd repositorio-local
    ```

3. <strong>Inicialize o repositório Git</strong>
    ```bash
    git init
    ```

    <em>(Isso cria um repositório vazio na pasta atual)</em>

4. <strong>Conecte ao repositório remoto (GitHub)</strong>
    ```bash
    git remote add origin https://github.com/seu-usuario/nome-repositorio.git
    ```

    <em>(Substitua a URL pela do seu repositório no GitHub)</em>

5. <strong>Verifique a conexão</strong>
    ```bash
    git remote -v
    ```

    <em>(Deve mostrar a URL do repositório remoto)</em>

<br>

<strong>✔️ Passo a Passo para Clonar um Repositório Existente:  
1. Abra o Git Bash</strong>
    - Execute o Git Bash na pasta onde deseja clonar o repositório.

2. <strong>Clone com o mesmo nome do repositório remoto</strong>
    ```bash
    git clone https://github.com/seu-usuario/repositorio-remoto.git
    ```

    <em>(Cria uma pasta com o mesmo nome do repositório remoto)</em>

3. <strong>Clone com nome personalizado</strong>
    ```bash
    git clone https://github.com/seu-usuario/repositorio-remoto.git nome-personalizado
    ```

    <em>(Substitua `nome-personalizado` pelo nome que desejar)</em>

4. <strong>Acesse o repositório clonado</strong>
    ```bash
    cd nome-do-repositorio
    ```
<br>

<strong>💡Observações Finais:</strong>
- **Para criar um repositório local**: Use `git init` + `git remote add origin URL`.
- **Para clonar um existente**: Use `git clone URL` (com ou sem nome personalizado).
- **Sempre verifique:**
  - Se está na pasta correta antes de executar os comandos (`cd`).
  - Se a URL do repositório remoto está correta (copia do GitHub).

</details>

## 💻 Aulas Completas

| Aulas | Links |
|-------|---------|
| O que é Versionamento de Código | [Vídeo](https://web.dio.me/track/bradesco-java-cloud-native/course/versionamento-de-codigo-com-git-e-github/learning/68183181-bc0a-4b66-a877-42dd42b5bc9c?autoplay=1) |
| Configurando o Git | [Vídeo](https://web.dio.me/track/bradesco-java-cloud-native/course/versionamento-de-codigo-com-git-e-github/learning/f9b294d2-f8ca-4364-9031-1e897721b3e2?autoplay=1) |
| Criando e Clonando Repositórios Locais/Remotos | [Vídeo](https://web.dio.me/track/bradesco-java-cloud-native/course/versionamento-de-codigo-com-git-e-github/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?autoplay=1) |
| Gravando Alterações no Repositório Local | [Vídeo](https://web.dio.me/track/bradesco-java-cloud-native/course/406684a4-396d-4160-94b9-ead934e18564/learning/599dd3dd-d189-474f-a55c-22f37b4472da?autoplay=1) |
