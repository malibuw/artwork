# `ASCII Bowtie Varients`


### Brick/Block
```text
                                                                                   
                             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                             
                             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                             
                             ▓▓▓███████████████████▓▓▓                             
             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓███████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓       
            ▓▓▓▓▓████████████████████████████████████████████████████▓▓▓▓▓▓        
           ▓▓▓▓▓████████████████████████████████████████████████████▓▓▓▓▓▓         
          ▓▓▓▓▓▓███████████████████████████████████████████████████▓▓▓▓▓▓          
         ▓▓▓▓▓▓███████████████████████████████████████████████████▓▓▓▓▓▓           
        ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓███████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓            
       ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓███████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓             
                             ▓▓▓███████████████████▓▓▓                             
                             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                             
                             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                             
```


### Minimal
```text

                             +++++++++++++++++++++++++                             
                             +++++++++++++++++++++++++                             
                             +++###################+++                             
             --+++++++++++++++++###################+++++++++++++++++++++++++       
            +----####################################################++++++        
           +---+####################################################++++++         
          ++++++###################################################++++++          
         ++++++###################################################++++++           
        ++++++++++++++++++++++++###################++++++++++++++++++++            
       +++++++++++++++++++++++++###################+++++++++++++++++++             
                             +++###################+++                             
                             +++++++++++++++++++++++++                             
                             #+++++++++++++++++++++++#                             
                                                                                
```

### Black/White
```text

                             █████████████████████████                             
                             █████████████████████████                             
                             █████████████████████████                             
             ███████████████████████████████████████████████████████████████       
            ███████████████████████████████████████████████████████████████        
           ███████████████████████████████████████████████████████████████         
          ███████████████████████████████████████████████████████████████          
         ███████████████████████████████████████████████████████████████           
        ███████████████████████████████████████████████████████████████            
       ███████████████████████████████████████████████████████████████             
                             █████████████████████████                             
                             █████████████████████████                             
                             █████████████████████████                                         
                                                                                
```

### Gray Scale
```text
                                                                                   
                             z|/////tt/t/tt/tt/tt////v                             
                             r){(((((((((((((((((()1|n                             
                             x((0mZmZmmZmmmmmmmmmm0)/n                             
             }_1)))))))))))))))(0mmmZZmZmmmmmmmmmm0)))))))((((((((((((()1}|j       
            )]]][QOZOZOOOOZOOOOOZmmmmZZZmZZmmmZmZmZOZOZOZOOZOZOZZZZOZv////c        
           t[[}{QmZmZmOmZZmZmZZmZmZZmZmOZZZmZmZmZmZmmmmZmZmZmmZmZmZZc|/ttv         
          /{{{1CZmZmZmZZZZmmZmZmZmZZmZmZZZZmZmZmmmmmmZmZmmZmZmmmZmmY|tttr          
         r))))XZZmOmZZOZZOmOZmZmOZZOmOZOZZOmOmOZZmZZmOmZmZZZOmZmmmC/ttfn           
        c/|||jXXXXXYXXYXXXYXYXYXOZmZmmmZmmZmZmZmmmOzXXXXXXXXXXXXXz(fffx            
       x/nczzzzzzXzzXXXXXXXXXzj|OZmZmZmmZmZmZmOZmm0/nXXXXXzXXXXzXzzznj             
                             ct/0ZmZmZmZZmZmZmZmZm0|fc                             
                             ctxccccccccccccccccvcvrtc                             
                             ZJYJJJJJJJJJJJJJJJJJJJYYZ                                                              
                                                                                
```

### Generate Terminal Centered
```bash
#!/usr/bin/env bash
clear

# Terminal dimensions
rows=$(tput lines)
cols=$(tput cols)

# ASCII art
art=(
"                             z|/////tt/t/tt/tt/tt////v                             "
"                             r){(((((((((((((((((()1|n                             "
"                             x((0mZmZmmZmmmmmmmmmm0)/n                             "
"             }_1)))))))))))))))(0mmmZZmZmmmmmmmmmm0)))))))((((((((((((()1}|j       "
"            )]]][QOZOZOOOOZOOOOOZmmmmZZZmZZmmmZmZmZOZOZOZOOZOZOZZZZOZv////c        "
"           t[[}{QmZmZmOmZZmZmZZmZmZZmZmOZZZmZmZmZmZmmmmZmZmZmmZmZmZZc|/ttv         "
"          /{{{1CZmZmZmZZZZmmZmZmZmZZmZmZZZZmZmZmmmmmmZmZmmZmZmmmZmmY|tttr          "
"         r))))XZZmOmZZOZZOmOZmZmOZZOmOZOZZOmOmOZZmZZmOmZmZZZOmZmmmC/ttfn           "
"        c/|||jXXXXXYXXYXXXYXYXYXOZmZmmmZmmZmZmZmmmOzXXXXXXXXXXXXXz(fffx            "
"       x/nczzzzzzXzzXXXXXXXXXzj|OZmZmZmmZmZmZmOZmm0/nXXXXXzXXXXzXzzznj             "
"                             ct/0ZmZmZmZZmZmZmZmZm0|fc                             "
"                             ctxccccccccccccccccvcvrtc                             "
"                             ZJYJJJJJJJJJJJJJJJJJJJYYZ                             "
)

# Center vertically
art_height=${#art[@]}
pad_rows=$(( (rows - art_height) / 2 ))
for ((i=0; i<pad_rows; i++)); do
  echo ""
done

# Colors
green=$'\e[92m'
reset=$'\e[0m'

# Center horizontally + print in green
for line in "${art[@]}"; do
  line_len=${#line}
  pad_cols=$(( (cols - line_len) / 2 ))
  printf "%s%s%s\n" "$(printf '%*s' $pad_cols '')" "${green}${line}${reset}"
done

# Lock the terminal
exec sleep infinity
```

---

**Disclaimer:**  
This project includes ASCII art inspired by the Chevrolet® bowtie emblem.  
Chevrolet and the bowtie logo are registered trademarks of General Motors.  
This ASCII art is for artistic and educational purposes only and is not  
affiliated with, endorsed by, or representative of General Motors.
