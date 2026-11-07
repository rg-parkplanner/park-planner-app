# park-planner-app

A static Telegram Mini App page for a personal theme-park day planner bot. It holds no data:
the bot passes the current plan in the link's fragment (after `#`), which browsers never send to
this host, and the page sends choices back to the bot through Telegram's `WebApp.sendData`.

Source of truth: `webapp/index.html` in the (private) planner repo; published with
`scripts/publish_webapp.sh`.
