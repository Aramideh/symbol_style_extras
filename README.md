# symbol_style_extras
Adding extra rotate and flip actions to symbol style editor ( admin application )


### Watch the demo video for explanation!

[![What this module do?](https://github.com/Aramideh/symbol_style_extras/blob/main/demo_image.png)](https://github.com/Aramideh/symbol_style_extras/blob/main/demo.mp4 "Symbol Style Extras")



#### how to use?


1.load the module
2.modify ...\sw_core\modules\sw_common\style_symbol_magik_gui\resources\base\data\symbol_editor_gui.xml


    <toolbar name="rotate">
		  <action name="symbols.symbol_flip_by_centre" mnemonic_id="flip_by_centre_m"/>
		  <action name="symbols.symbol_rotate_clockwise_by_centre" mnemonic_id="rotate_clockwise_by_centre_m"/>
		  <action name="symbols.symbol_rotate_clockwise" mnemonic_id="rotate_clockwise_m"/>
		  <action name="symbols.symbol_rotate_counter_clockwise" mnemonic_id="rotate_counter_clockwise_m"/>
    </toolbar>
    
    
  <dock name="top">
    <!-- other toolbars in the doc -->
	  <toolbar name="rotate"/>
    </dock>
