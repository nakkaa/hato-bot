# Setting to Event URL

1. [Slack API: Applications | Slack](https://api.slack.com/apps) を開きます。

1. 左側にある `Event Subscriptions` をクリックします。

1. `Enable Events` をOnにします。

1. `Request URL` にHerokuのURLを入力します。この時、以下の様にURL末尾に `slack/events` を追加します。

    ```text
    https://example.herokuapp.com/slack/events
    ```

1. `Verified` が表示されたら下にある `Subscribe to bot events` をクリックし `app_mention` を追加します。

1. `Save Changes` をクリックします。
