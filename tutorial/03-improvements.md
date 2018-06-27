# Further improvements

This section contains a few links to documentation you can read if you're
interested in any of the additional features that Actions on Google gives you.

## Audio effects

The Assistant can also reply with special audio effects, mixed together with or
separately from your conversation.

To know how to add audio to your conversation, check the official
[Speech Synthesis Markup Language (SSML) documentation](https://developers.google.com/actions/reference/ssml).

## Add cards

Instead of replying with a simple text or voice, you can consider adding special
cards to your Action, that will be displayed on phones:

![](https://developers.google.com/actions/images/geeknum-card.svg)

For instance, you can display the username of the user in a title, and the tweet
in a smaller text size.

You can also think of adding the profile image of the user as the card image,
or a button that links to the tweet.

Check the [Response documentation](https://developers.google.com/actions/assistant/responses)
for more information.

## Give different answers according to device

Using the [Capabilities API](https://developers.google.com/actions/assistant/surface-capabilities),
you can check if the device supports audio or has a screen.

This will allow you to give different responses according to the device, e.g.
a shorter audio if the device has a screen, as the user can read a card.
