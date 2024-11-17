
If the photo is still in the middle, it could be due to the way GitHub renders Markdown and inline HTML. GitHub doesn't fully support all CSS properties, especially for complex layouts like flexbox.

To ensure the image aligns to the top-right, a simpler approach using a table-like structure can work better, as GitHub supports basic HTML tables. Here's an alternative solution:

html
複製程式碼
<table width="100%">
  <tr>
    <td align="left">
      <h1>Hi, Natsuha Yap here!</h1>
      <p>🌟 42 Malaysia Cadet</p>
      <p>🚀 Exploring Coding | Passionate about AI & Mobile Dev</p>
      <p>🎸 Fan of Neuro-sama && Evil Neuro || Nijika Ijichi</p>
      <p>🎨 PFP Creds | X @eenightlamp</p>
    </td>
    <td align="right">
      <img src="https://github.com/natsuhakoishi/natsuhakoishi/blob/main/srcs/natsuha.jpg" alt="Top Right Photo" width="150">
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://github.com/natsuhakoishi/natsuhakoishi/blob/main/srcs/neuro.gif" alt="Evil" width="400">
  <img src="https://github.com/natsuhakoishi/natsuhakoishi/blob/main/srcs/evil.gif" alt="Neuro" width="400">
</p>
