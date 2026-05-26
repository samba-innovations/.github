<div align="center">

<img src="imgs/innvtns-logotipo2.svg" height="56" alt="samba innovations" />

<br/><br/>

**Tecnologia que resolve.**

Desenvolvemos plataformas digitais integradas para transformar a gestão escolar — do planejamento pedagógico à portaria, passando por avaliações, ocorrências e comunicação.

<br/>

[![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma&logoColor=white)](https://www.prisma.io/)

</div>

---

## Ecossistemas

Operamos dois ecossistemas independentes — uma plataforma genérica multi-escola e uma implementação dedicada para a EE Prof. Christino Cabral.

---

### samba innovations — Plataforma Multi-Escola

Ecossistema genérico, multi-tenant, projetado para ser implantado em qualquer escola. Cada sistema é um submodule Git independente, orquestrado por Docker Compose, com banco PostgreSQL compartilhado e SSO centralizado.

> 9 sistemas ativos · 2 escolas · 44+ usuários · 2.829 aulas curriculares

<br/>

<table>
<tr>
<td align="center" width="160">
<b>landing</b><br/>
<sub>Portal público e identidade visual da plataforma</sub>
</td>
<td align="center" width="160">
<b>sso</b><br/>
<sub>Login unificado — JWT compartilhado entre todos os sistemas</sub>
</td>
<td align="center" width="160">
<b>hub</b><br/>
<sub>Painel administrativo — escolas, usuários e sistemas</sub>
</td>
</tr>
<tr>
<td align="center" width="160">
<img src="imgs/control-logo2.svg" height="36" alt="control" /><br/>
<b>control</b><br/>
<sub>Frequência de alunos, carômetro e gestão de turmas</sub>
</td>
<td align="center" width="160">
<img src="imgs/gate-logo2.svg" height="36" alt="gate" /><br/>
<b>gate</b><br/>
<sub>Portaria eletrônica — entradas, saídas e custódia</sub>
</td>
<td align="center" width="160">
<b>mockflow</b><br/>
<sub>Simulados e avaliações com gabarito automático e leitura óptica</sub>
</td>
</tr>
<tr>
<td align="center" width="160">
<img src="imgs/reserve-logo2.svg" height="36" alt="reserves" /><br/>
<b>reserves</b><br/>
<sub>Reserva de espaços e recursos da escola</sub>
</td>
<td align="center" width="160">
<img src="imgs/code-logo2.svg" height="36" alt="occurrences" /><br/>
<b>occurrences</b><br/>
<sub>Registro e acompanhamento de ocorrências disciplinares</sub>
</td>
<td align="center" width="160">
<b>less</b><br/>
<sub>Planejamento pedagógico, documentos PEI e horários</sub>
</td>
</tr>
</table>

<br/>

→ [github.com/samba-innovations/samba-innovations](https://github.com/samba-innovations/samba-innovations)

---

### samba.escolacabral — EE Prof. Christino Cabral

Implementação dedicada para a Escola Estadual Prof. Christino Cabral (Bauru, SP). 11 aplicações integradas em servidor dedicado, com autenticação unificada e backup horário automático.

> 15 containers · 64 usuários · 3.476 aulas curriculares · 99/99 health checks ✔

<br/>

<table>
<tr>
<td align="center" width="160">
<b>samba-access</b><br/>
<sub>SSO — autenticação unificada com JWT HS256 para todo o ecossistema</sub>
</td>
<td align="center" width="160">
<img src="imgs/paper-logo2.svg" height="36" alt="samba-paper" /><br/>
<b>samba-paper</b><br/>
<sub>Documentação pedagógica — planos de aula, PEI, guias e ATAs em PDF/DOCX</sub>
</td>
<td align="center" width="160">
<img src="imgs/control-logo2.svg" height="36" alt="samba-control" /><br/>
<b>samba-control</b><br/>
<sub>Gestão de alunos, responsáveis, carômetro e alunos PEI</sub>
</td>
</tr>
<tr>
<td align="center" width="160">
<img src="imgs/gate-logo2.svg" height="36" alt="samba-gate" /><br/>
<b>samba-gate</b><br/>
<sub>Portaria inteligente — entradas/saídas, chamados e custódia</sub>
</td>
<td align="center" width="160">
<img src="imgs/edvance-logo2.svg" height="36" alt="samba-edvance" /><br/>
<b>samba-edvance</b><br/>
<sub>Avaliações e simulados alinhados ao BNCC/SAEB com leitura óptica de gabaritos</sub>
</td>
<td align="center" width="160">
<img src="imgs/code-logo2.svg" height="36" alt="samba-code" /><br/>
<b>samba-code</b><br/>
<sub>Ocorrências disciplinares e pedagógicas com workflow de resolução</sub>
</td>
</tr>
<tr>
<td align="center" width="160">
<b>samba-admin</b><br/>
<sub>Administração de usuários, roles e permissões por sistema</sub>
</td>
<td align="center" width="160">
<img src="imgs/flourish-logo2.svg" height="36" alt="samba-flourish" /><br/>
<b>samba-flourish</b><br/>
<sub>Monitoramento ambiental via sensores IoT — temperatura e umidade</sub>
</td>
<td align="center" width="160">
<img src="imgs/pombo-logo1.svg" height="36" alt="pombo-christino" /><br/>
<b>pombo-christino</b><br/>
<sub>Sistema de comunicados internos da escola</sub>
</td>
</tr>
</table>

<br/>

→ [github.com/samba-innovations/samba.escolacabral](https://github.com/samba-innovations/samba.escolacabral)

---

## Stack

| Camada | Tecnologias |
|--------|-------------|
| **Frontend & Backend** | Next.js 15 (App Router · Server Actions) · TypeScript 5 · CSS Modules |
| **Banco de dados** | PostgreSQL 16 · Prisma ORM · schemas isolados por domínio |
| **Autenticação** | JWT HS256 via jose · SSO com tokens de uso único |
| **Infraestrutura** | Docker Compose · nginx (reverse proxy · SSL/TLS) · MinIO (S3) |
| **Geração de documentos** | PDFKit · docx.js |
| **Serviços especializados** | Python 3.12 · FastAPI · OpenCV (leitura óptica de gabaritos) |
| **Backup** | PostgreSQL dump horário · GitHub (orphan commits) · retenção 7 dias |
| **Segurança** | fail2ban · scram-sha-256 · headers HTTP · auditoria mai/2026 — 0 vulnerabilidades críticas |

---

<div align="center">

<img src="imgs/innvtns-logo2.svg" height="28" alt="samba innovations" />

&nbsp;&nbsp;**samba innovations** · Bauru, São Paulo · Brasil

</div>
