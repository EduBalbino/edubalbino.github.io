---
title: Como Realizar Modificações na Wiki?
tags:
- setup
---

>[!INFO] Não é simples
Mas também não é difícil.

# Setup do GitHub
O GitHub do Fórmula-E Siará possui total acesso aos arquivos que compõem o site. Portanto, o primeiro passo deve ser fazer o login no mesmo.

## [GitHub Desktop](https://desktop.github.com/)
Além do acesso ao GitHub pelo navegador, torna-se necessário a instalação do GitHub Desktop para a atualização dos arquivos da Wiki.

Após [baixar o GitHub Desktop](https://desktop.github.com/), é necessário realizar a clonagem do repositório:

>[!NOTE]- Selecionando repositório correto
>![Select Correct Repository](notes/images/github-desktop-setup-tutorial.png)

# [Obsidian](http://obsidian.md)

Obsidian é a melhor forma de realizar alterações na Wiki, por já podermos ter uma prévia de como a página se tornará. Entretanto, se você estiver se sentindo **valente** pode até mesmo realizar as modificações nos arquivos ```.md``` pelo navegador ou Notepad.

Após [baixar e instalar o Obsidian](https://obsidian.md/download) 

## Settings
Great, now that you have your Obsidian linked to your Quartz, let's fix some settings so that they play well.

1. Under Options > Files and Links, set the New link format to always use Absolute Path in Vault.
2. Go to Settings > Files & Links > Turn "on" automatically update internal links.

![Obsidian Settings](/notes/images/obsidian-settings.png)*Obsidian Settings*

## Templates
Inserting front matter everytime you want to create a new Note gets annoying really quickly. Luckily, Obsidian supports templates which makes inserting new content really easily.

**If you decide to overwrite the `/content` folder completely, don't remove the `/content/templates` folder!**

Head over to Options > Core Plugins and enable the Templates plugin. Then go to Options > Hotkeys and set a hotkey for 'Insert Template' (I recommend `[cmd]+T`). That way, when you create a new note, you can just press the hotkey for a new template and be ready to go!

1. Obsidian é um programa com vários objetivos, seja para anotações, criação de mapas mentais e, no nosso caso, criação de uma base de conhecimento.
2. Não é estritamente necessário a instalação do programa, mas ajuda **e muito** na edição dos arquivos.