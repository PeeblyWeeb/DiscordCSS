<img width="1921" height="1075" alt="image" src="https://github.com/user-attachments/assets/23023f5f-ef4a-4484-bede-f9ff59a9d56a" />
<sub>preview with `quick.css` & `links.css` fully enabled</sub>

---

> [!NOTE]
> This CSS alone can only make the Discord client transparent; Since the client can't actually see what is behind itself, external software is required to apply blur behind it.
> 
> You can use: [Mica for Everyone (windows)](https://github.com/MicaForEveryone/MicaForEveryone) or [Better Blur DX (linux)](https://github.com/xarblu/kwin-effects-better-blur-dx) / [KWin Effects Glass (linux)](https://github.com/4v3ngR/kwin-effects-glass)

# How to use (Vencord Instructions)

1. Navigate to `User Settings > Themes (under vencord) > Online Themes`
2. Paste `https://raw.githubusercontent.com/PeeblyWeeb/DiscordCSS/refs/heads/main/main.css` into the text box
3. Leave the text-box and everything should work just fine

## `Quick.css`
I've also published my personal quickcss to this repository for anybody to use!

The recommended way to use it is to just look through the file and pick and choose what you want and paste it into your client's quickcss.

If you *really* want everything (including automatic updates), you can put: `https://raw.githubusercontent.com/PeeblyWeeb/DiscordCSS/refs/heads/main/quick.css` into your "Online Themes" section

You should also enable window transparency in `User Settings > Vencord > Enable window transparency`

## Contributing

> [!WARNING]
> The `:has()` CSS selector is frowned upon in this repository due to its high performance cost, please avoid using it
>
> If your contribution would benefit from this selector and there is no other alternative, feel free to PR it as commented code that people can opt-in to

**I am not accepting PR's to `quick.css`. Any PR's targeting `quick.css` will be immediately closed.**

If you'd like to contribute some CSS to this repository there's basically only two rules you have to follow:
- Organize your code properly.
- The change must be universally agreeable, if you're unsure if your change is, just make a pr and i'll lyk.
