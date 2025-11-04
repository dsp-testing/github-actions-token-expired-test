# github-actions-token-expired-test
Expecting if one action calls token expired, Rest should fail on expired token workflow should fail

1. Call public action and ensure it's working as expected with dependabot
2. Call private action and ensure it's woring as expected with dependabot.
3. Now update the token, which fails to access private
4. But public should pass. (Customer complained it's not working in https://github.com/dependabot/dependabot-core/issues/13166)
