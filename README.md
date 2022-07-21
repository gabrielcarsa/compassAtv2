# Compass: Instalação Oracle Linux

## 1. Selecionar o idioma do sistema

O primeiro passo ao instalar o Linux é selecionar a língua, deixei a padrão, inglês.

![lingua](https://user-images.githubusercontent.com/63206031/180288251-b0ad0303-e882-42bb-b2ff-a780f1f6133e.png)

## 2. Menu Geral

Após selecionar o idioma aparecerá essa tela com varias opções de configurações.

![geral](https://user-images.githubusercontent.com/63206031/180309604-7aa392cf-6297-48f4-975a-e7f75cbe749a.png)

## 3. Escolher o software para instalar (Installation Source)

Agora vamos escolher o software que será instalado, como é um servidor, selecione a opção 'Minimal Install'.

![minimal](https://user-images.githubusercontent.com/63206031/180310026-fc387105-94f9-4535-9724-8aa0a1a41b7e.png)

## 4. Partição do Disco (Installation Destionation)

Aqui é feito a partição do disco, selecione a opção 'custom' para particionar de maneira customizada. A partição que fiz está na imagem abaixo. Coloquei os diretório: /var, /tmp, /, /boot,/home e /var/lib/docker (ext4).
Você pode particionar conforme a capacidade do seu disco.

![particao](https://user-images.githubusercontent.com/63206031/180310680-f586e863-36ea-4e90-84af-15b928a9bd28.png)

## 5. Rede (Network & Host Name)

Na parte de rede, apenas ativei a interface de rede que por padrão vem desativada.

![internet](https://user-images.githubusercontent.com/63206031/180311154-5b2fedee-e7dd-4af3-a389-3149d1a82361.png)

## 6. Passos Finais

Após seguido os passos feitos até aqui, basta colocar uma senha para o root e se desejar adicionar um novo usuário. No meu caso adicionei um novo usuário e marquei a opção para deixar ele com privilégios de sudo.

Também alterei o teclado para Português, pois esse é o teclado que eu uso. Por fim, só clicar 'Begin Installation' e pronto.
