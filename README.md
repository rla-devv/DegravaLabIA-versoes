# Degrava Lab IA — versões

Pacotes da instalação e da atualização automática do Degrava Lab IA. Não há código-fonte aqui.

- `Degrava Lab IA.zip`: a instalação (só o `Instalar Degrava Lab IA.bat`, que baixa o resto);
  `DegravaIA.zip`, `DegravaLab.zip` e `DegravaLabIA.zip` são a mesma, com os nomes antigos do app;
- `atualizacao.json`: a versão mais recente, o SHA-256 do pacote e as novidades
  (é o que o app consulta);
- `versoes/`: o pacote de código de cada versão;
- `modelos/`: o modelo de interlocutores pyannote/speaker-diarization-community-1,
  sem alterações (licença CC-BY-4.0; crédito em `modelos/LICENCA-pyannote.txt`).

Cada versão também é uma Release (tag `vX.Y.Z`) com o instalador (`Degrava Lab IA.zip`), o pacote de
código e o modelo de interlocutores (`pyannote-*`): a instalação e a atualização baixam de lá.

Publicado pelo `publicar.py` do repositório do código.
