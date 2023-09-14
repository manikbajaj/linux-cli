# Solutions: Quoting and Escaping

### Solutions to Exercise Questions

1. `echo "The value of \$HOME is: $HOME"`

2. `echo "That's all, folks!"` or `echo 'That'\''s all, folks!'`

3. ```bash
   greeting="world"
   echo "Hello, $greeting!"
   echo 'Hello, '"$greeting"'!'
   ```

4. `echo "She said, \"Hello, world!\""`

5. `echo -e "First Line.\cSecond Line."`

6. `echo -e "Apple\n\tBanana\n\tCherry"`

7. `echo -e "\f" > page_break.txt`

8. `echo -e "\a"`
