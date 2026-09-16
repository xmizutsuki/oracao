# Salah — Guia de Orações

Web app em português para acompanhar as cinco orações diárias do Islã.

## Recursos

- Horários diários de Fajr, Dhuhr, Asr, Maghrib e Isha.
- Localização por cidade ou geolocalização do navegador.
- Métodos de cálculo configuráveis e opção Hanafi para Asr.
- Checklist diário com progresso de 0/5 a 5/5.
- Histórico local dos últimos 28 dias.
- Guia passo a passo de cada Salah obrigatória.
- Modo de aprendizado que não altera o histórico.
- Direção aproximada da Qiblah calculada localmente.
- Data Hijri retornada junto aos horários.
- Sem login e sem banco de dados: preferências e histórico ficam no `localStorage`.
- Layout responsivo para celular e desktop.

## Como usar

O projeto é estático. Abra `index.html` em um servidor web ou publique com GitHub Pages.

Para publicar no GitHub Pages, nas configurações do repositório escolha **Pages > Deploy from a branch > main / root**.

## Fonte dos horários

Os horários são consultados na API pública do AlAdhan. O usuário pode escolher o método de cálculo no próprio aplicativo. Diferenças de alguns minutos podem existir conforme a autoridade religiosa ou mesquita local.

## Observação religiosa

O guia foi criado como ferramenta educacional e apresenta uma forma amplamente ensinada da Salah sunita. Existem diferenças legítimas entre escolas jurídicas e comunidades; dúvidas específicas devem ser confirmadas com uma mesquita ou pessoa qualificada.
