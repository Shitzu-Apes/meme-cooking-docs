---
title: How It Works
icon: ":mortar_board:"
order: 1
---

# 🎓 How It Works

*Not too complex, actually.*

When a token is created, a countdown is started for 5 minutes, 1 hour, or 1 day. During that time, other people can deposit and withdraw NEAR to this meme token, if they want to buy it.

* If by the end of the countdown, the token has less than 4,000 NEAR (total), all NEAR is refunded to participants, and the token is not launched.
* If it has more than 4,000 NEAR deposited, the token is launched, the deposited NEAR (excl. protocol fee) and 50% of token supply is deposited on Ref, the LP is locked for 8 years, and the other 50% of tokens is distributed to depositors proportionally to their deposit. If you deposit twice as much NEAR, you get twice as much tokens.

You can withdraw your NEAR before the countdown ends, but you will be penalized with 2% fee for doing so. This fee will be distributed to other people who have the NEAR deposited at the moment when the countdown ends, no matter if the token is launched or not.

```mermaid
%%{
  init: {
    'theme': 'forest',
    'themeVariables': {
      'background': '#333',
      'primaryTextColor': '#333',
      'fontSize': '30px'
    }
  }
}%%
graph TD;
    A(Token is created)-->B(People deposit NEAR);
    B-->C{Reached 4,000 NEAR}
    C-->|No| D(Token is not launched)
    D-->E(Depositors are refunded,<br />no withdrawal fee charged)
    C-->|Yes| F(Token is launched)
    F-->G(50% of tokens are locked in Ref LP)
    G-->H(50% of tokens are sent to depositors)

```

If the token doesn't make it to 4,000 NEAR, anyone can revive it using “Relaunch” button, which creates a new token with the same name, ticker, and other details, and the countdown starts again. Depositors need to actively withdraw their NEAR on the accounts page.

If the token reaches the necessary deposit amount of 4,000 NEAR, then they can claim their token on the accounts page. Tokens will not be distributed automatically.

### Examples

Example 1:

* Someone creates a meme token with 1-day countdown
* The token peaks at 69,000 NEAR total deposited
* The meme fell off, almost everyone has withdrawn everything, only 700 NEAR is left when the countdown ends
* The token is not launched, the last believers who didn't withdraw, are fully refunded (except for the 0.5% fee)

Example 2:

* Someone creates a meme token with 1-hour countdown
* Insiders snipe 25,000 NEAR worth of it
* \<insert your favorite CT influencer> calls it, pumping the deposit amount to 30,000 NEAR
* After the countdown ends, 100% of deposited NEAR and 50% of tokens are deposited and locked on Ref, and users claim their share of tokens at a market cap of 59,700 NEAR
* Insiders bought at the same price as everyone else, and if they dump right after the token launched, they will end up at a loss
