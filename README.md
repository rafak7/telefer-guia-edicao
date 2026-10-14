# Como funciona o Elementor na Telefer

Documentação do modelo **híbrido**: tema Telefer + Elementor página a página.

**Guia completo:** https://rafak7.github.io/telefer-guia-edicao/

## Em uma frase

Páginas institucionais já estão no Elementor (widgets Telefer). Blog, header, menu e rodapé continuam no tema.

## O que editar onde

| Conteúdo | Ferramenta |
| --- | --- |
| Home, Sobre, Soluções, Cloud, IA, Contato | **Editar com Elementor** (widgets Telefer) |
| Página nova no Elementor | **Editar com Elementor** |
| Artigos do Blog | WordPress → **Posts** |
| Header / menu / rodapé | Tema (não é Theme Builder ainda) |

## Widgets Telefer

No painel do Elementor, busque **Telefer**:

- Hero de página
- Formulário de lead
- Grade de soluções
- Seção do tema

## Fluxo básico

1. https://telefer.com.br/wp-admin/
2. Páginas → abrir a página → **Editar com Elementor**
3. Clicar no widget → alterar campos → **Atualizar**
4. Conferir no site com hard refresh ou `?telefer_nocache=1`

## Backup pré-Elementor

- Tema: `wp-content/themes/telefer-pre-elementor-20261014/`
- Tarball: `public_html/_backups/telefer-theme-pre-elementor-20261014-165906.tar.gz`

## Observações

- **Presença Digital** foi removida; redireciona para `/solucoes/`.
- Soluções ativas: Telefer Cloud e Telefer com IA.
