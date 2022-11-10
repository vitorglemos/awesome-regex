# Awesome Regex

## Hash regex match

- **Bycript**: `[$]2[aby]?\$\d{1,2}\$[.\/A-Za-z0-9]{53}`, **match**: `$2a$10$cFcbvhfTyJXYq2dh2/EFeeI9uabkuoZpL.7R0vmBEUyVCBILBkjwa`
- **SHA256**: `\b[A-Fa-f0-9]{64}\b`, **match**: `7f83b1657ff1fc53b92dc18148a1d65dfc2d4b1fa3d677284addd200126d9069`
- **SHA1**: `\b[0-9a-f]{5,40}\b` **match**: `2ef7bde608ce5404e97d5f042f95f89f1c232871`
- **MD5**: `^[a-f0-9]{32}$`, **match**: `ed076287532e86365e841e92bfc50d8c`

## Email Validation 
- **Email**: `[a-zA-Z0-9._-]{3,}@[a-zA-Z0-9.-]{3,}\.[a-zA-Z]{2,4}`, **match**: `testvalidation@gmail.com`
