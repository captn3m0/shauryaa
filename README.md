# [shauryaa.in](https://shauryaa.in)

Website for my niece. I decided to make this as a gift
to my sister and brother-in-law. Other than the website,
which is a standard jekyll website with little content
as of now, I was inspired by this [Google Ad][ad],
where parents send their daughter emails as she is
growing up. I wanted to replicate something similar.

[![Youtube Ad](https://shauryaa.in/assets/img/youtube-ad.jpg)][ad]

## Email Setup

I used [migadu][migadu] for email hosting. I
wanted a reasonably cheap service, and one I can
trust to be around for a while. I really like
their stance on privacy and other matters (like
how they have a drawbacks page).

Also, if you want to try this, I'd recommend
against using GMail for your kid because
[google doesn't allow kids to create accounts][tc]

It automatically let me create the standard
admin emails (`{admin|postmaster|hostmaster}@`).

I created the following additional email
addresses:

- <mom@shauryaa.in> - Forwards to my sister's email
- <dad@shauryaa.in> - Forwards to my brother in law's email
- <parents@shauryaa.in> - Forwards to both of the above
- <mail@shauryaa.in> - Forwards to <parents@shauryaa.in>, with the idea that this will point to <shauryaa@shauryaa.in> once she is old enough to use it.
- <shauryaa@shauryaa.in> - Primary email. This is the one I'm writing mails to. Both parents have access to this, but ideally I want this to be write-only.
- <sherry@shauryaa.in>, <shaurya@shauryaa.in> - Both are aliases to the above. Sherry is her nickname, and I expect "Shaurya" to be a common misspelling.
- <mama@shauryaa.in> - This forwards to my primary email account. (Mama is hindi for "paternal uncle")
- All the `admin@` mails are forwarded to me as well.

## Credits

- Based on https://github.com/willianjusten/will-jekyll-template
- Instagram icon from https://codepen.io/ruandre/pen/howFi
- Color theme suggested by @vikalp03
- The 

[ad]: https://www.youtube.com/watch?v=R4vkVHijdQk
[migadu]: https://www.migadu.com/en/index.html
[tc]: https://techcrunch.com/2011/05/09/attention-dear-sophie-inspired-parents-you-cant-actually-create-a-google-account-for-your-kid/