# Redux - Asynchronous Actions

## How granular should your reducers be?

> Both the Redux core library and most of the Redux documentation are unopinionated. There are many ways to use Redux, and much of the time there is no single “right” way to do things.

> However, time and experience have shown that for some topics, certain approaches work better than others. In addition, many developers have asked us to provide official guidance to reduce decision fatigue.*

## Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

> This is a Con because you may fire off reducers that you did not intend

## Name a strategy for preventing the above

> you should have one reducer to deal with one state usually.

