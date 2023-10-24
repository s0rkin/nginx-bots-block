<h2>INFO</h2>
<p>Some filtered bots, get 444 answer's on request's.</p>

<h2>HOT TO USE</h2>
<p>STEP 1</p>
<p>in /etc/nginx/nginx.conf add:</p>
<code>include /etc/nginx/bots.conf;</code>

![Screenshot_4](https://github.com/s0rkin/nginx-bots-block/assets/12657938/4b35f369-26bc-4ee0-bdaf-0350f4df6f7b)

<p>STEP 2</p>
<p>in your sites-available conf's add:</p>
<code>include /etc/nginx/rules.conf;</code>

<h3>change 444 answer</h3>
<code>edit in bot.conf return 444;</code>

<h2>RESULT</h2>

![Screenshot_6](https://user-images.githubusercontent.com/12657938/218886145-c53c09be-836b-44c2-9642-eb1c0c10f00b.png)
