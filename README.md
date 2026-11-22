# agenda-airbnb

Painel dos anúncios Airbnb (Studios M1, M2, M3 — São Pedro/SP).

- `index.html` — página inicial, com links pras outras 3.
- `agenda.html` — calendário de reservas/bloqueios (export oficial iCal do
  Airbnb — sem preço, sem nome de hóspede).
- `precos.html` — médias praticadas, preços de concorrentes cadastrados
  (registrados manualmente) e sugestão de preço pros próximos 45 dias.
- `tudo.html` — versão compacta com agenda + preços juntos, ~45 dias.

Atualizado automaticamente todo dia às 7h por um script agendado no PC
local (`airbnb-saopedro/publicar.py`, via Tarefa Agendada do Windows
"AgendaAirbnb"). Os preços próprios vêm de uma captura pontual (não se
atualizam sozinhos); concorrentes são o que for registrado manualmente com
`airbnb.bat log-comp`.

Ver ao vivo: https://douglastomieiro.github.io/agenda-airbnb/
