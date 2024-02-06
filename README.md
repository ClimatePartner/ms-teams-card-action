<p>
  <a href="https://github.com/ClimatePartner/ms-teams-deploy-card/actions"><img alt="ms-teams-deploy-card status" src="https://github.com/gor918/ms-teams-deploy-card/workflows/Build%20&%20Test/badge.svg"></a>
</p>

Usage:
```yaml
- name: Microsoft Teams Notifications DC
  uses: ClimatePartner/ms-teams-deploy-card@main
  with:
    github-token: ${{ github.token }} # this will use the runner's token.
    ms-teams-webhook-uri: ${{ secrets.MS_TEAMS_WEBHOOK_URI }}
    notification-summary: Your custom notification message 
    notification-color: 17a2b8
    timezone: Europe/Bucharest
```