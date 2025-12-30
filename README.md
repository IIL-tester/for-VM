# Store the original logo in a variable
LOGO_CONTENT=$(cat ~/.config/fastfetch/ascii-art.txt.bak)

# Overwrite the main file with 4 copies + newlines for spacing
echo "$LOGO_CONTENT" > ~/.config/fastfetch/ascii-art.txt
echo "" >> ~/.config/fastfetch/ascii-art.txt
echo "$LOGO_CONTENT" >> ~/.config/fastfetch/ascii-art.txt
echo "" >> ~/.config/fastfetch/ascii-art.txt
echo "$LOGO_CONTENT" >> ~/.config/fastfetch/ascii-art.txt
echo "" >> ~/.config/fastfetch/ascii-art.txt
echo "$LOGO_CONTENT" >> ~/.config/fastfetch/ascii-art.txt
