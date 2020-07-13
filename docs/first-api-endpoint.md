---
id: first-api-endpoint
title: Your first API endpoint
---

**Concepts:** Structural elements, blanks, implicit returns, traces.

1. Create a new HTTP endpoint from the omnibox (click anywhere on the screen or
   hit `Cmd-k`/`Ctrl-k`), or from the plus next to `HTTP` on the sidebar.

![gettingstarted/Screen_Shot_2020-02-11_at_9.10.26_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.10.26_AM.png)

2. Enter the HTTP verb as `GET` and `/math` for the route.

![gettingstarted/Screen_Shot_2020-02-11_at_9.11.23_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.11.23_AM.png)

3. You can now write any code in the blank &ndash; this is the return value of
   the API endpoint that you've just created. To start with, let's just return
   `4`.

![gettingstarted/Screen_Shot_2020-02-11_at_9.12.02_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.12.02_AM.png)

4. Click the handler's menu (☰) in the upper right and select "open in new tab",
   to see your API endpoint running in production.

![gettingstarted/Screen_Shot_2020-02-11_at_9.12.43_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.12.43_AM.png)

5. Go back to Dark to edit your code. Add `+ 5` to the end of the code and leave
   your cursor in line.

![gettingstarted/Screen_Shot_2020-02-11_at_9.14.25_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.14.25_AM.png)

- The `9` below the handler shows you the return value for the handler.

- The `5` on the left shows you the result of the expression where the cursor
  currently is (in this case, 5). This isn't very useful when it's an integer,
  but if it's a variable it will show you the result of the variable.

![gettingstarted/Screen_Shot_2020-02-11_at_9.16.06_AM.png](/docs/img/gettingstarted/Screen_Shot_2020-02-11_at_9.16.06_AM.png)

6. Mouse over the white dots on the left. Each dot is a "trace", representing a
   single request to your handler. Traces are fundamental to coding in Dark, and
   we'll come back to them later.

Congratulations! You've shipped your first Dark API endpoint.
