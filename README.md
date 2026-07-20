# AutoBot Scalper — BTC/ETH, 1m/5m (GitHub Actions edition)

Second, fully separate paper desk: $2,000 account locked to BTC and
ETH on scalping timeframes (1m or 5m, bot-chosen). Same self-learning
loop, same IC Markets spread costs (BTC 0.02%, ETH 0.16% round trip).

Setup: identical to the main autobot repo.
1. Create a new PUBLIC repo (e.g. "autobot-scalper"); upload bot/,
   docs/, requirements.txt, README.md
2. Create .github/workflows/bot.yml with the contents of
   SETUP-workflow.yml
3. Settings -> Secrets and variables -> Actions -> New repository
   secret: ANTHROPIC_API_KEY (same key as the other repo)
4. Settings -> Pages -> Deploy from a branch -> main / /docs
5. Actions -> trading-bot -> Run workflow
Dashboard: https://YOURUSERNAME.github.io/autobot-scalper/
