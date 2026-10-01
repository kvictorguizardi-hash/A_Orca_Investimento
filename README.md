# A Orca 🐋

Carteira de investimentos com IA que monitora notícias das empresas e alerta quando a tese de investimento original deixa de fazer sentido.

## Sobre o projeto

A maioria das ferramentas de carteira mostra só números: cotação, lucro, prejuízo. O A Orca vai além: para cada ativo, você registra **por que** decidiu investir nele. Uma IA interna acompanha as notícias e avalia se os motivos originais continuam válidos, sinalizando quando uma tese de investimento se enfraquece ou é quebrada.

## Funcionalidades

- [x] Cadastro de ativos da carteira
- [ ] Registro da tese de investimento por ativo
- [ ] Busca automática de notícias das empresas cadastradas
- [ ] Análise de risco via IA (grau de investibilidade)
- [ ] Alertas visuais quando a tese é comprometida

## Stack utilizada

- [Next.js](https://nextjs.org/) (React + App Router)
- [Supabase](https://supabase.com/) (banco de dados PostgreSQL + autenticação)
- [Tailwind CSS](https://tailwindcss.com/)
- [Anthropic Claude API](https://www.anthropic.com/) (análise de notícias)

## Status do projeto

🚧 Em desenvolvimento. Este é um projeto pessoal, em construção ativa.

## Como rodar localmente

\`\`\`bash
npm install
npm run dev
\`\`\`

Crie um arquivo `.env.local` na raiz com as variáveis:

\`\`\`
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=
\`\`\`

## Aviso importante

Este projeto é para uso pessoal e fins de estudo. **Não constitui recomendação de investimento.** As análises geradas por IA podem conter erros e não substituem decisões próprias ou orientação profissional.

## Autor

Desenvolvido por [kvictorguizardi-hash](https://github.com/kvictorguizardi-hash)
