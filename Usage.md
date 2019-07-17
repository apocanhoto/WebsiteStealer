# Usage

usage: webscreenshot [-h] [-i INPUT_FILE] [-o OUTPUT_DIRECTORY] [-w WORKERS]
                     [-v] [-r {phantomjs,chrome,chromium,firefox}]
                     [--renderer-binary RENDERER_BINARY] [--no-xserver]
                     [--window-size WINDOW_SIZE] [-p PORT] [-s] [-m]
                     [-c COOKIE] [-a HEADER] [-u HTTP_USERNAME]
                     [-b HTTP_PASSWORD] [-P PROXY] [-A PROXY_AUTH]
                     [-T PROXY_TYPE] [-t TIMEOUT]
                     [URL]


# Renderer

phantomjs is the best renderer for this python script.

-r phantomjs

# Cookies

cookie:


becomes:

-c 

# Output
-o ~/Downloads/WebsiteName/



# Command

webscreenshot <URL> -r phantomjs -c "[cookie]" -o ~/Downloads/[WebsiteName]/

