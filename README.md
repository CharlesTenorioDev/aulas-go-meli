# aulas-go-meli
Aulas de Golang para BootCamp

# 💻 Já estudou programação hoje?  

🌟 **Está fazendo o diário de bordo do que aprendeu?**  

---

## ❓ Questões sobre Criação de Pacotes e Declaração de Variáveis em Golang

1. 🗂 **O que é um pacote em Golang e qual a sua importância em um programa?**
    Packages são arquivos fontes de um mesmo diretório, entre eles o package main, pacotes nativos e pacotes próprio criados
2. 🏗 **Como declarar e utilizar o pacote principal (`main`) em uma aplicação Go?**
package main
func main(){

}
3. 🔄 **Qual é a diferença entre pacotes internos (_standard library_) e pacotes personalizados em Go?**
pacotes internos vem dentro de cada projeto de Go para utilizar precisamos apenas chamar dentro do código.
pacotes personalizados devem ser puxados através do **go get** e atualizados pelo go mod tidy
4. 📦 **Como importar e utilizar um pacote externo no Go?** *(Dê um exemplo.)*
***go get*** e dentro do código chamar o pacote importando para dentro do pacote necessário
5. ⚙️ **Qual é o comando utilizado no Go para inicializar um novo módulo e gerenciar dependências?**
go mod init <nome do módulo>
6. 🚫 **O que acontece se você importar um pacote no Go e não utilizá-lo no código?**
Erro de compilação até ser retirado pelo próprio Go
7. 🌍 **Como declarar uma variável global em um pacote e torná-la acessível a outros pacotes?**
Letra maióscula na primeira letra
8. ✍️ **Qual a diferença entre uma variável declarada com `var` e uma variável inicializada com `:=` em Go?**
atribuição dinamica e colocado na tipagem padrão a depender do tipo de dado colocado
9. 🔓 **Como você exporta uma variável ou função de um pacote em Golang, e qual a convenção de nomenclatura para isso?**
Letra maiúscula e utilização de camelCase
10. 🕶 **Explique o conceito de _shadowing_ (sombras) em relação às variáveis no Go e como isso pode afetar o escopo.**
Shadowing é quando a variavel de escopo mais restrito tem precedencia sobre a variavel de escopo mais amplo

---

### 🚀 **Você é seu maior investimento, então bora fazer render!** 😄

---
