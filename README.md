<p>
  <a href="https://github.com/ClimatePartner/ms-teams-card-action/actions"><img alt="ms-teams-card-action status" src="https://github.com/ClimatePartner/ms-teams-card-action/workflows/Build%20&%20Test/badge.svg"></a>
</p>

Usage:
```yaml
- name: Microsoft Teams Notifications DC
  uses: ClimatePartner/ms-teams-card-action@main
  with:
    github-token: ${{ github.token }} # this will use the runner's token.
    ms-teams-webhook-uri: ${{ secrets.MS_TEAMS_WEBHOOK_URI }}
    notification-summary: Your custom notification message 
    notification-color: 17a2b8
    timezone: Europe/Bucharest
```