# Heroku Image-Optim Buildpack

Add binaries for image-optim on Herokug

- advpng
- gifsicle
- jhead
- jpegoptim
- jpegtran
- optipng
- pngcrush

Binaries are in this git repo in vendor/image-optim

On compilation :

- Binaries are copied into vendor/image-optim
- version of each binaries is displayed
- vendor/image-optim is added to path through a .profile.d script
