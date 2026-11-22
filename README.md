# agenda-airbnb

Painel dos anúncios Airbnb (Studios M1, M2, M3 — São Pedro/SP).

- `index.html` — página única com tudo junto: agenda (calendário de 6 meses,
  export oficial iCal do Airbnb — sem preço, sem nome de hóspede), preços,
  concorrentes, média regional e sugestão de preço.
- `agenda.html` — só o calendário, separado.
- `precos.html` — só a parte de preços, separada.

Atualizado automaticamente 2x por dia (7h e 22h) por um script agendado no PC
local (`airbnb-saopedro/publicar.py`, via Tarefa Agendada do Windows
"AgendaAirbnb"). Os preços próprios vêm de uma captura pontual (não se
atualizam sozinhos); concorrentes são o que for registrado manualmente com
`airbnb.bat log-comp`.

Ver ao vivo: https://douglastomieiro.github.io/agenda-airbnb/
