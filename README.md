find . -type f \( -iname "*.jpg" -o -iname "*.jpeg" \) -exec jpegoptim --strip-all {} \;