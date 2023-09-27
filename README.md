<div id="header" align="center">
  <img src=https://github.com/4i8/4i8/assets/76555623/69991054-bad8-425d-b85a-471ecc351209" width="200"/>
	<p> M<strong>a</strong>gic of <strong>th</strong>e Joke<strong>r</strong>🎩🃏</p>
  <div id="badges">
<a href="https://discord.com/users/599882913064026153#804291489319616512">
    <img src="https://img.shields.io/badge/discord-black?style=for-the-badge&logo=discord&logoColor=white" alt="discord"/>
  </a>
  <a href="https://www.npmjs.com/~iarth">
    <img src="https://img.shields.io/badge/npm-black?style=for-the-badge&logo=npm&logoColor=white" alt="Npm"/>
  </a>
  <a href="https://twitter.com/rrarth">
    <img src="https://img.shields.io/badge/Twitter-black?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
</div>
</div>

##
`Arth.sh`
 ```bash
#!/bin/bash
binary_string="01000011 01101111 01100100 01100101 00100000 01101001 01110011 00100000 01110100 01101000 01100101 00100000 01100011 01101001 01100111 01100001 01110010 01100101 01110100 01110100 01100101 00100000 01110100 01101000 01100001 01110100 00100000 01101110 01100101 01110110 01100101 01110010 00100000 01101100 01100101 01100001 01110110 01100101 01110011 00100000 01101101 01111001 00100000 01101000 01100001 01101110 01100100 "

# Split the binary string into an array
binary_array=($binary_string)

# Initialize an empty variable for the text
text=""

# Iterate through the binary values and convert to text
for binary_value in "${binary_array[@]}"; do
    # Convert binary to decimal and then to ASCII character
    decimal_value=$((2#$binary_value))
    text+=$(printf "\\$(printf '%03o' "$decimal_value")")
done

# Print
echo -e "\"$text🚬\"\n- Arth\n"
```

##

<p><strong>RUN</strong></p>

```bash
bash Arth.sh
```

##

<p><strong>OUTPUT</strong></p>

```
Code is the cigarette that never leaves my hand🚬
- Arth
```

##

<p><strong>SKILLS</strong></p>

[![My Skills](https://skillicons.dev/icons?i=js,html,css,wasm,py,rust,ts,nodejs,deno,regex,electron,express,graphql,jquery,react,redux,nextjs,sass,bootstrap,materialui,tailwind,mongodb,mysql,postgres,sqlite,prisma,linux,bash,nginx,docker,git,github,postman,neovim,vscode,gcp)](https://skillicons.dev)
