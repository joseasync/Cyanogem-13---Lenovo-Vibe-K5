#Cyanogen-13---Lenovo-Vibe-K5
Fluxo de Instalação da Rom Cyanogem no Lenovo Vibe K5 / How to install Cyanogem in Lenovo Vibe K5 PLUS


## <b>Lembrando que este tutorial é de caráter didático, não me responsabilizo pelo seu aparelho ao efetuar este procedimento</b>

<b><i>Antes de tudo vamos ser coleguinhas ::::</i></b>  [@jricardorp1](https://twitter.com/JRicardoRP1)


<b>Requisitos:</b>
* Sistema Operacional Windows 7/8/10.
* ROM Cyanogen 13 - [Link na Descrição]
* SuperSU v2.46- [Link na Descrição]
* Minimal ADB FastBoot - [Link na Descrição]
* Imagem TWRP - [Link na Descrição]
* Gapps ARM64 Pico -  [Link NA Descrição]


<b>1.1 Configurações prévias no Aparelho</b>
- Em seu aparelho :
- Ative as opções de Desenvolvedor (Configurações>Sobre o Telefone>Informações do dispostivo> Toque 7 vezes em "Número da versão")
- Ative a Depuração USB
- Ative a opção de Desbloqueio OEM
- Conecte o Celular no PC pelo Cabo USB
- Instale os Drivers que vem na partição CD do próprio celular (Meu computador>Lelnovo>"Nome do instalador do Drive"



<b>1.2 Instação/Utilização do TWRP</b>
- Efetue o Download e instalação do [Minimal ADB FastBoot](https://drive.google.com/open?id=0B-OBLhHCytuvVVlod0cxaDhKOTQ) <<Download
- Baixe o arquivo  [twrp-k5-3.0.2-r1_shreps.img](https://drive.google.com/open?id=0B-OBLhHCytuvWW1mUFpXRGRoSDg) <<Download
- Assim que baixado coloque-o dentro da pasta do Minimal ADB (Normalmente a pasta seria: "C:\Program Files (x86)\Minimal ADB and Fastboot")
- Assim que efetuar a instalação do Minimal e copiado o arquivo. Entre dentro da pasta onde foi efetuada a instalação. Normalmente a pasta seria: "C:\Program Files (x86)\Minimal ADB and Fastboot".
- Dentro da pasta Aperte SHIFT + Botao direito do mouse e clique em "Abrir janela de comando aqui".
- Este comando irá abrir o Terminal. 
- Digite o comando "<i><b>adb devices </b></i>". Este comando irá listar os aparelhos conectados ao PC, certifique-se que o seu esteja conectado (o nome não irá condizer com o modelo).
- Digite então o comando  "<i><b>adb reboot bootloader</b></i>" para reiniciar em modo Bootloader (Irá reiniciar o aparelho e ficar na tela Branca da lenovo aguardando o proximo comando...)
- Enquanto a tela do celular estiver com a logo da Lenovo digite então no terminal o comando "<i><b>fastboot boot twrp-k5-3.0.2-r1_shreps.img</b></i>". Este comando irá inicializar o menu do TWRP no smartphone Selecione o idioma e vc será direcionado ao menu principal.
- Enquanto isso irá aparecer no "Meu computador" a pasta do aparelho entre e cole dentro da pasta TWRP os arquivos baixados:
- | [cm-13.0.1-20160804-UNOFFICIAL-A6020.zip] (https://drive.google.com/open?id=0B-OBLhHCytuvSkk2aVppd0Jjck0) <<Download
- | [open_gapps-arm64-6.0-pico-20160805.zip](https://drive.google.com/open?id=0B-OBLhHCytuvX2drS2hrSjJ6ajQ) <<Download
- | [UPDATE-SuperSU-v2.46.zip](https://drive.google.com/open?id=0B-OBLhHCytuvTmtPelFLclhSWFU) <<Download


<b>1.3 Instação do ROOT (SuperSU V2.46)</b>
- Em seu vibe K5 no Menu do TWRP, toque em Install, vá no zip do SuperSu (Na pasta onde vc colou os arquivos acima), confirme a instalação e após isso clique em Limpar Cache/Dalvik.
- Limpando o Cache/Dalvik selecione a opção "reiniciar Sistema"

<b>1.3 Instação da ROM Cyanogem 13 & Gapps</b>
- Efetue o passo 1.2 <b>NOVAMENTE</b>
- Obs: <b>NÃO É NECESSÁRIO COPIAR OS ARQUIVOS NOVAMENTE</b>
- Após efetuar o procedimento 1.2 e estar no Menu do TWRP novamente, va em "Apagar Cache" e após isso em "Apagar Avançado" ou "wipe avançado" (no menu avançado jovem...rsrs)
- E marque as seguintes opções:
- ~Dalvik Cache
- ~Dados 
- ~Cache 
- ~Sistema
- Após selecionar vá em <b>apagar</b>
- Voltando ao menu principal toque em Install e selecione <b>PRIMEIRAMENTE</b> o arquivo da ROM:  cm-13.0.1-20160804-UNOFFICIAL-A6020.zip.
- Após a instalação limpe o Cache/Dalvik novamente. <b>Desta vez NÃO É NECESSÁRIO REINICIAR O SISTEMA</b>.
- Agora voltando ao menu principal toque em Install e selecione o arquivo dos Gapps: open_gapps-arm64-6.0-pico-20160805.zip
- Após a instalação limpe o Cache/Dalvik novamente.
- Finalizado a limpeza selecione <b>Reiniciar o sistema</b>


<b>Parabéns Voce esta com a Cyanogen 13 Instalada em seu Lenovo Vibe K5, foi um sucesso !!! </b>

<b><i>Duvidas, questionamentos, intrigas, feedbacks:</i></b>  [@jricardorp1](https://twitter.com/JRicardoRP1)
