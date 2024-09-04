---
created: 03-09-2024
---
## **Introdução**
O **Sn1per** é uma ferramenta de automação de reconhecimento e coleta de informações usada em testes de penetração e avaliações de segurança. Criada por **xer0dayz**, o Sn1per é amplamente utilizado por profissionais de segurança cibernética para automatizar tarefas de reconhecimento e identificar vulnerabilidades em ambientes complexos.
![Sniper_Run](https://github.com/AnubisChacal/O4rculumD3i/blob/main/Ferramentas/Path-1/PRINTs/Pasted%20image%2020240903210330.png)

### **Menção ao Criador:**
- **GitHub:** [https://github.com/1N3/Sn1per](https://github.com/1N3/Sn1per)
- **Site:** [https://sn1persecurity.com/wordpress/](https://sn1persecurity.com/wordpress/)
- **X (Twitter):** [https://x.com/xer0dayz](https://x.com/xer0dayz)
- **Bugcrowd:** [https://bugcrowd.com/1N3](https://bugcrowd.com/1N3)
- **Hackerone:** [https://hackerone.com/xer0dayz?type=user](https://hackerone.com/xer0dayz?type=user)
- **LinkedIn:** [https://www.linkedin.com/in/sn1persecurity/](https://www.linkedin.com/in/sn1persecurity/)

## **Instalação** 🛠️
A instalação do Sn1per requer algumas dependências para garantir o funcionamento adequado. As principais dependências incluem:

### **Dependências:**
- **Git:** Para clonar o repositório Sn1per.
- **Docker (opcional):** Recomendado para executar o Sn1per em um ambiente isolado.
- **Nmap:** Utilizado para escaneamento de rede.
- **Metasploit Framework:** Para exploração automatizada.
- **Python 3.x e Pip:** Necessário para executar scripts e módulos adicionais.
- **Amass:** Para coleta de informações sobre domínios.
- **Subfinder:** Ferramenta para busca de subdomínios.
- **Aquatone:** Para tirar screenshots de sites.

### **Passos de Instalação:**
1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/1N3/Sn1per.git
   cd Sn1per
   ```

2. **Instale as Dependências:**
   ```bash
   sudo apt update
   sudo apt install -y git nmap python3 python3-pip
   sudo apt install -y metasploit-framework
   ```

3. **Instale o Sn1per:**
   ```bash
   sudo bash install.sh
   ```

4. **Configuração Adicional:**
   - Instale as ferramentas opcionais (Amass, Subfinder, Aquatone) conforme necessário para o seu ambiente.

## **3. Funcionalidades Principais** ⚙️
O Sn1per oferece uma série de funcionalidades que facilitam o reconhecimento e a coleta de informações em um ambiente de teste de penetração:

- **Reconhecimento Automatizado** 🔍: Executa tarefas de reconhecimento com um único comando, identificando subdomínios, portas abertas, serviços, e outras informações críticas.
- **Exploração de Vulnerabilidades** 🔥: Integra-se com Metasploit para automatizar a exploração de vulnerabilidades conhecidas.
- **Coleta de Informações sobre Domínios** 🌐: Usa ferramentas como Amass e Subfinder para mapear a superfície de ataque de um domínio.
- **Análise de URLs e Aplicações Web** 🌐: Suporta a verificação de URLs e aplicativos web, identificando falhas de segurança comuns.
- **Relatórios Detalhados** 📄: Gera relatórios organizados e detalhados dos resultados, facilitando a análise e o compartilhamento das descobertas.

## **4. Casos de Uso** 🔍
O Sn1per pode ser usado em uma variedade de cenários de segurança ofensiva:

- **Reconhecimento em Testes de Penetração**: Automatiza a fase inicial de reconhecimento em um teste de penetração, acelerando o processo e garantindo que nenhuma superfície de ataque seja deixada de lado.
- **Auditorias de Segurança de Aplicações Web**: Identifica vulnerabilidades em aplicações web, como SQL Injection, Cross-Site Scripting (XSS), e outras falhas comuns.
- **Avaliações de Segurança de Infraestrutura**: Mapeia redes internas e externas, identificando portas abertas, serviços vulneráveis, e outras falhas de configuração.

## **5. Conclusão** ✅
O Sn1per é uma ferramenta essencial para qualquer profissional de segurança que busca automatizar o processo de reconhecimento e coleta de informações. Ele se destaca por sua capacidade de integração com outras ferramentas e por gerar relatórios detalhados que facilitam a análise dos resultados.

### **Futuras Melhorias:**
Uma possível atualização para o Sn1per seria a integração com uma plataforma web open-source, permitindo que os resultados das análises sejam visualizados e gerenciados através de uma interface web. Isso não só melhoraria a acessibilidade dos dados, mas também facilitaria a colaboração entre equipes de segurança e a análise de grandes volumes de dados em projetos complexos.
