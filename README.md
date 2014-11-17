jquery-contextual-menu
=

A configurable context menu. It act on right click, hover (with time lag), hold (with lag)

text.html show hold with 1sec of lag.

The project home is in http://www.smartango.com/articles/jquery-context-menu


USE:
---

    func1= function(event, element) { };
    func2= function(event, element) { };
    jQuery(".linkimg").contextmenu({'option 1':func1,
                              'option 2':func2},
                              'hold',1000);

Second option is 'hold','right' or 'hover'

Parameters are passed to callback function
=

Callback function has event and element as input. The ratio is to have, say, the exact position where pointer was when right clicked (i.e. use it in canvas too)
