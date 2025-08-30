-----

# 📖 Guia de Instalação - SKYRIM V4 MODPACK

*Desenvolvido por **MaxTR***

Obrigado pelo seu interesse no modpack\! Este guia contém instruções cruciais para garantir que sua instalação seja rápida e sem erros. **Por favor, leia com atenção antes de começar.**

-----

## 🚀 Comece Por Aqui: Como Obter Seu Instalador Pessoal

O instalador pessoal é **exclusivo para apoiadores do projeto**, pois garante um acesso seguro e direito a suporte. Para se tornar um apoiador e receber seu instalador, escolha uma das opções abaixo:

### Opção 1: Apoio via Patreon

1.  Acesse nosso Patreon: [**patreon.com/maxtrmodpacks**](https://patreon.com/maxtrmodpacks)
2.  Apoie qualquer um dos níveis disponíveis (Bronze, Silver, etc.).
3.  Após a confirmação, entre em contato comigo pelo **Discord** para receber seu instalador pessoal e sua senha de acesso.

### Opção 2: Apoio via PIX

1.  Entre em contato comigo via mensagem privada no Discord (**maxtr**) para solicitar a chave PIX.
2.  Após realizar o apoio, envie o comprovante na nossa conversa.
3.  Você receberá seu instalador pessoal e sua senha de acesso.

> **Não é Apoiador?** Se você tem interesse ou dúvidas sobre o modpack, me chame no privado do Discord (**maxtr**) ou deixe um comentário no YouTube.

-----

## ❤️ Apoio Adicional (Para Apoiadores Atuais)

Se você já é um apoiador e deseja contribuir ainda mais para o desenvolvimento e manutenção do modpack, sua ajuda é muito bem-vinda\!

**Chave PIX (Copia e Cola):**

```
4a8ec02a-6cf6-4440-92c5-2b7a52ceb63a
```

*Muito obrigado pelo seu suporte contínuo\!*

-----

## 🚨 AVISO CRÍTICO: Antivírus e Falsos Positivos

> Devido à forma como o instalador foi programado (para proteger senhas e automatizar tarefas), alguns programas de antivírus podem sinalizá-lo incorretamente como uma ameaça.
>
> **ISTO É UM "FALSO POSITIVO". O INSTALADOR É 100% SEGURO.**
>
> Para garantir que a instalação funcione, **RECOMENDAMOS FORTEMENTE DESATIVAR SEU ANTIVÍRUS TEMPORARIAMENTE** ou adicionar uma **EXCEÇÃO DE SEGURANÇA** para a pasta onde você vai executar o instalador.

-----

## 🧹 Pré-Instalação: Fazendo uma Limpeza Completa

> **[LEIA OBRIGATORIAMENTE SE VOCÊ JÁ USOU OUTROS MODPACKS]**
> Para evitar conflitos, é **ESSENCIAL** garantir que não há resquícios de instalações antigas do Mod Organizer 2 (MO2).

#### Opção 1 (Recomendada - Automática):

1.  Execute o arquivo `limpeza_mo2.bat` que veio junto com este pacote.
2.  É **altamente recomendável** executá-lo como **Administrador** (clique direito -\> "Executar como administrador").
3.  Leia o aviso que ele exibe e pressione `S` para confirmar.

#### Opção 2 (Alternativa - Manual):

1.  Pressione as teclas `Windows + R` para abrir a caixa "Executar".
2.  Digite `%LOCALAPPDATA%` e pressione Enter. Na pasta que abrir, encontre e **EXCLUA** a pasta `ModOrganizer`.
3.  Faça o mesmo para `%APPDATA%`.

> **Atenção:** Este processo removerá permanentemente perfis e configurações de **QUALQUER** outro modpack que utilize o MO2.

-----

## ✅ Checklist de Requisitos

#### 📝 Software (Instale ANTES de Começar)

  - [ ] **Visual C++ Redistributable (x64)**
      - **Link:** [Microsoft VC++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)
      - *(Na página, baixe e instale a versão **X64**).*
  - [ ] **.NET 8.0 Desktop Runtime (x64)**
      - **Link:** [Download .NET 8.0](https://dotnet.microsoft.com/pt-br/download/dotnet/8.0)
      - *(Baixe o **".NET Desktop Runtime"** para Windows x64).*
  - [ ] **.NET Framework 4.8.1**
      - **Link:** [Download .NET Framework 4.8.1](https://dotnet.microsoft.com/pt-br/download/dotnet-framework/net481)
      - *(Normalmente já vem com o Windows, mas instale para garantir).*
  - [ ] **Cópia do Skyrim da Steam**
      - O instalador precisa que o jogo base (`Skyrim Special Edition` ou `Anniversary Edition`) esteja instalado para funcionar como "hook".

#### 🗂️ Arquivos e Acesso

  - [ ] **O Pacote do Instalador:** O `.zip` que você recebeu de mim, contendo:
      - `Instalador-seu-nome-id.exe`
      - `7z.exe`
      - `7z.dll`
  - [ ] **Os Arquivos do Modpack:** Todas as partes (`.7z.001`, `.002`, etc.) baixadas dos links oficiais.
  - [ ] **Espaço em Disco:** Pelo menos **300 GB** livres no HD/SSD de instalação.
  - [ ] **Sua Senha de Acesso:** A senha pessoal e única que eu forneci a você junto com o instalador.

-----

## ⚙️ Guia de Instalação: Passo a Passo

**1. Crie uma Pasta Temporária**
Crie uma nova pasta em um local de fácil acesso (Ex: `C:\InstalacaoSkyrim`).

**2. Junte TUDO na Mesma Pasta**
Este é o passo mais importante\! Coloque **TODOS** os arquivos (o `Instalador.exe`, `7z.exe`, `7z.dll` e **TODAS AS PARTES DO MODPACK**) dentro desta pasta.

**3. Execute como Administrador**
Clique com o botão direito no `Instalador-seu-nome-id.exe` e selecione **"Executar como administrador"**.

**4. Siga as Instruções na Tela**
A partir daqui, o instalador é autoexplicativo. Ele pedirá sua senha pessoal, a unidade de disco e cuidará de todo o resto.

> **Paciência\!** A extração dos arquivos pode levar **HORAS**, dependendo do seu computador. É normal.

-----

## 🤔 Solução de Problemas (FAQ)

  - **"O antivírus apagou o `Instalador.exe`\!"**

    > Volte à seção de aviso sobre antivírus. Você precisará desativá-lo temporariamente ou criar uma exceção de segurança.

  - **"O instalador fecha sozinho\!"**

    > Certifique-se de que você está executando como **Administrador**.

  - **"Deu erro de 'ESPAÇO INSUFICIENTE'\!"**

    > Você precisa liberar o espaço indicado no disco que escolheu, ou selecionar outra unidade.

  - **"Deu 'ERRO NA EXTRAÇÃO'\!"**

    > Um dos arquivos `.7z.00X` está corrompido ou faltando. Tente baixá-lo novamente.

  - **"Meu 'ACESSO EXPIROU'\!"**

    > As licenças de acesso têm validade. Entre em contato para renovar seu acesso.

-----

## 💬 Suporte e Contato

Se você é um apoiador oficial e seguiu todos os passos, mas ainda precisa de ajuda, entre em contato:

  - **Discord (Preferencial):** `maxtr`
  - **E-mail:** `contato@modpacks.com.br`
  - **YouTube:** [Canal MaxTR](https://www.youtube.com/@MaxTR)

> **Ao pedir suporte, por favor, informe o ID de 3 dígitos do seu instalador.** (Ex: `001`, `042`, `123`).

## 🎉 Aproveite o Jogo\!
