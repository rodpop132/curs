# Nômade Milionário Legacy - Plataforma de Curso

Este é um site para assistir ao curso Nômade Milionário Legacy online, organizado por módulos e vídeos, pronto para deploy na Vercel.

## Como usar

1. **Preencha os links dos vídeos**
   - Abra o arquivo `src/data/course.json`.
   - Para cada vídeo, cole o link de compartilhamento do Google Drive no campo `driveUrl`.
   - O link deve estar no formato de embed do Google Drive:
     - Exemplo: `https://drive.google.com/file/d/ID_DO_VIDEO/preview`
   - Para obter esse link:
     1. No Google Drive, clique com o botão direito no vídeo > "Obter link".
     2. Copie o ID do vídeo do link compartilhável.
     3. Monte o link de embed: `https://drive.google.com/file/d/ID_DO_VIDEO/preview`

2. **Rodando localmente**
   - Instale as dependências:
     ```bash
     npm install
     ```
   - Rode o servidor de desenvolvimento:
     ```bash
     npm run dev
     ```
   - Acesse [http://localhost:3000](http://localhost:3000)

3. **Deploy na Vercel**
   - Faça login em [vercel.com](https://vercel.com/)
   - Importe este repositório
   - Deploy automático

## Estrutura do projeto
- `src/data/course.json`: Organização dos módulos e vídeos
- `src/pages/index.js`: Página inicial (lista de módulos)
- `src/pages/modulo/[id].js`: Página de cada módulo (lista e player dos vídeos)

---

Dúvidas? Só pedir! 