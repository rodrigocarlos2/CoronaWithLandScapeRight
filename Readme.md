
For use a application in LandScape Mode, acess:

https://docs.coronalabs.com/guide/distribution/buildSettings/index.html#androidsettings

Or in Build Settings, make:

settings ={    
    orientation =    {        
        default = "landscapeRight",        
        supported = { "landscapeLeft", "landscapeRight" }    
    },
}

And for Main.lua, develop with way:

local webView = native.newWebView(display.contentCenterX, display.contentCenterY, display.contentWidth, display.contentHeight)webView:request("https://test1-c3f44.firebaseapp.com/")
