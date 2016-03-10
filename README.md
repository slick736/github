sfyc
====
var ua = navigator.userAgent.toLowerCase();
var textSprite = new Sprite();
textSprite.bitmap = new Bitmap(816, 64);
textSprite.x = 0;
textSprite.y = 0;
textSprite.anchor.x = 0;
textSprite.anchor.y = 0;
textSprite.width = 816;
textSprite.height = 64;
this.addChild(textSprite);
textSprite.bitmap.outlineWidth = 8;
textSprite.bitmap.fontSize = 24;
textSprite.bitmap.drawText(ua, 0, 0, 816, 64);
