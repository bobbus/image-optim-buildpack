# Heroku Image-Optim Buildpack

Add binaries for image-optim on Herokug

- advpng
- gifsicle
- jpegoptim
- jpegtran
- optipng
- pngcrush

Binaries are in this git repo in vendor/image-optim

On compilation :

- Binaries are copied into vendor/image-optim
- Symlink to binaries is added to ensure next buildpacks will have binaries available
- vendor/image-optim is added to PATH through a .profile.d script
- Version of each binaries is displayed


