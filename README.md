# Como funciona o Elementor na Telefer

Documentação do modelo **híbrido**: tema Telefer + Elementor página a página.

**Guia completo:** https://rafak7.github.io/telefer-guia-edicao/

## Em uma frase

Se a página foi publicada no Elementor, o site mostra o Elementor. Se não, continua o layout PHP atual.

## O que editar onde

| Conteúdo | Ferramenta |
| --- | --- |
| Página institucional migrada no Elementor | **Editar com Elementor** |
| Página ainda não migrada | Continua no tema PHP (ou migre no Elementor) |
| Artigos do Blog | WordPress → **Posts** |
| Header / menu / rodapé | Tema (não é Theme Builder ainda) |

## Fluxo básico

1. https://telefer.com.br/wp-admin/
2. Páginas → abrir a página → **Editar com Elementor**
3. Alterar / montar seções → **Publicar**
4. Conferir no site com hard refresh ou `?telefer_nocache=1`

## Backup pré-Elementor

- Tema: `wp-content/themes/telefer-pre-elementor-20261014/`
- Tarball: `public_html/_backups/telefer-theme-pre-elementor-20261014-165906.tar.gz`

## Observações

- **Presença Digital** foi removida; redireciona para `/solucoes/`.
- Soluções ativas: Telefer Cloud e Telefer com IA.
