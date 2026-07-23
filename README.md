![Capa do currículo](capa.png)

# Currículo em LaTeX — Pedro Augusto Hackner Bittencourt

Este repositório contém meu currículo profissional desenvolvido em **LaTeX**, utilizando a classe **moderncv** (tema *classic*). O projeto é totalmente local, organizado e pronto para compilação com distribuições como MiKTeX ou TeX Live.

## Conteúdo

- Arquivo principal: `main.tex`
- Estrutura baseada em **moderncv**
- Seções do currículo:
  - Perfis online
  - Objetivo profissional
  - Formação acadêmica
  - Experiência profissional
  - Habilidades técnicas
  - Cursos e certificações
  - Atividades extracurriculares
  - Idiomas

## Estrutura de arquivos

```
Curriculo_Pedro_LaTeX/
├── main.tex        # Documento principal
├── capa.png        # Foto da capa
└── README.md
```

## Pré-requisitos

Antes de iniciar, certifique-se de possuir as seguintes ferramentas instaladas no seu ambiente:

- [Git](https://git-scm.com/) (para realizar a clonagem do repositório).
- Uma distribuição LaTeX, como [TeX Live](https://tug.org/texlive/) (Linux/Windows), [MiKTeX](https://miktex.org/) (Windows/macOS) ou [MacTeX](https://tug.org/mactex/) (macOS).

## Como clonar o repositório

Para obter uma cópia local deste projeto, abra o seu terminal e execute o seguinte comando:

```bash
git clone https://github.com/PedroAHB/Curriculo_Pedro_LaTeX.git
```

## Como compilar

Após clonar o repositório, navegue até a pasta do projeto e execute o comando de compilação:

```bash
# Navega para o diretório clonado
cd Curriculo_Pedro_LaTeX

# Compila o documento e gera o arquivo PDF
pdflatex main.tex
```

*Observação técnica: Em projetos LaTeX, ocasionalmente é necessário executar o comando `pdflatex main.tex` duas vezes consecutivas na primeira compilação para garantir que o layout e os metadados internos da classe moderncv sejam perfeitamente alinhados.*

## Uso deste repositório

Este projeto é pessoal e reflete meu currículo individual. Caso deseje utilizá-lo como base para o seu próprio currículo, será necessário substituir todas as informações pessoais, de contato e de experiência presentes em `main.tex`.


