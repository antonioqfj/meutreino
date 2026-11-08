# Meu Treino — app local para iPhone

App simples para organizar exercícios por dia da semana, marcar séries concluídas e cronometrar o descanso. Os dados ficam no armazenamento local do navegador no aparelho.

## Instalar no iPhone

1. Publique esta pasta em uma hospedagem estática com HTTPS (por exemplo, um espaço privado seu) ou sirva-a temporariamente por um computador na mesma rede.
2. Abra o endereço no Safari do iPhone.
3. Toque em **Compartilhar → Adicionar à Tela de Início**.
4. Abra pelo ícone **Meu Treino**. Depois que carregar uma vez, os arquivos do app ficam disponíveis offline.

O iOS exige um endereço seguro (HTTPS) para habilitar instalação como app e funcionamento offline pelo service worker. A pasta também pode ser aberta como página web, mas nesse caso a instalação e o modo offline podem não funcionar.

## Uso

- Selecione um dos sete dias e toque em **＋ Exercício**.
- Informe nome, séries, repetições e, se quiser, carga ou observação.
- Toque em cada série para marcar/desmarcar como feita. A marcação fica salva no aparelho.
- Ajuste minutos e segundos no cronômetro e toque em **Começar**. O botão alterna para pausar/continuar; **Zerar** volta ao tempo escolhido.
- O som de alerta é gerado pelo próprio app e sai pela saída de áudio selecionada pelo iPhone, incluindo fones conectados.

## Limite do cronômetro no iPhone

Para o aviso tocar no horário, mantenha o app aberto e a tela ativa. O iOS pode suspender páginas web quando você troca de app ou bloqueia a tela, então o cronômetro não é confiável em segundo plano. O app tenta manter a tela acesa enquanto conta, quando o navegador permite.

