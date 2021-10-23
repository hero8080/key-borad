<template>
  <div class="g_full_screen flex_content_center g_bgcolor_bg">
    <div class="key_main g_bgcolor_key_bg flex g_pad12 g_radius4 text_center">
      <!--   键盘左侧   -->
      <div class="key_left flex1 flex_column">
        <!--   上   -->
        <div class="key_height flex border border_items_right_none">
          <div class="flex1 g_bgcolor_main">Esc</div>
          <div class="key_esc_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_key_grey">F1</div>
          <div class="flex1 g_bgcolor_key_grey">F2</div>
          <div class="flex1 g_bgcolor_key_grey">F3</div>
          <div class="flex1 g_bgcolor_key_grey">F4</div>
          <div class="key_f_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_main">F5</div>
          <div class="flex1 g_bgcolor_main">F6</div>
          <div class="flex1 g_bgcolor_main">F7</div>
          <div class="flex1 g_bgcolor_main">F8</div>
          <div class="key_f_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_key_grey">F9</div>
          <div class="flex1 g_bgcolor_key_grey">F10</div>
          <div class="flex1 g_bgcolor_key_grey">F11</div>
          <div class="flex1 g_bgcolor_key_grey">F12</div>
        </div>
        <div class="g_wid12_h"></div>
        <!--   下   -->
        <div class="flex1 flex_column">
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="flex1 g_bgcolor_key_blue g_color_main">~</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">1</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">2</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">3</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">4</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">5</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">6</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">7</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">8</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">9</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">0</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">-</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">+</div>
            <div class="key_backspace_width g_bgcolor_key_blue g_color_main">Backspace</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_tab_width g_bgcolor_key_blue g_color_main">Tab</div>
            <div class="flex1 g_bgcolor_key_grey">Q</div>
            <div class="flex1 g_bgcolor_key_grey">W</div>
            <div class="flex1 g_bgcolor_key_grey">E</div>
            <div class="flex1 g_bgcolor_key_grey">R</div>
            <div class="flex1 g_bgcolor_key_grey">T</div>
            <div class="flex1 g_bgcolor_key_grey">Y</div>
            <div class="flex1 g_bgcolor_key_grey">U</div>
            <div class="flex1 g_bgcolor_key_grey">I</div>
            <div class="flex1 g_bgcolor_key_grey">O</div>
            <div class="flex1 g_bgcolor_key_grey">P</div>
            <div class="flex1 g_bgcolor_key_grey">[</div>
            <div class="flex1 g_bgcolor_key_grey">]</div>
            <div class="key_tab_width g_bgcolor_key_blue g_color_main">\|</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_caps_width g_bgcolor_key_blue g_color_main">Caps</div>
            <div class="flex1 g_bgcolor_key_grey">A</div>
            <div class="flex1 g_bgcolor_key_grey">S</div>
            <div class="flex1 g_bgcolor_key_grey">D</div>
            <div class="flex1 g_bgcolor_key_grey">F</div>
            <div class="flex1 g_bgcolor_key_grey">G</div>
            <div class="flex1 g_bgcolor_key_grey">H</div>
            <div class="flex1 g_bgcolor_key_grey">J</div>
            <div class="flex1 g_bgcolor_key_grey">K</div>
            <div class="flex1 g_bgcolor_key_grey">L</div>
            <div class="flex1 g_bgcolor_key_grey">;</div>
            <div class="flex1 g_bgcolor_key_grey">"</div>
            <div class="key_enter_width g_bgcolor_key_blue g_color_main">Enter</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_shift_width g_bgcolor_key_blue g_color_main">Shift</div>
            <div class="flex1 g_bgcolor_key_grey">Z</div>
            <div class="flex1 g_bgcolor_key_grey">X</div>
            <div class="flex1 g_bgcolor_key_grey">C</div>
            <div class="flex1 g_bgcolor_key_grey">V</div>
            <div class="flex1 g_bgcolor_key_grey">B</div>
            <div class="flex1 g_bgcolor_key_grey">N</div>
            <div class="flex1 g_bgcolor_key_grey">M</div>
            <div class="flex1 g_bgcolor_key_grey">,</div>
            <div class="flex1 g_bgcolor_key_grey">.</div>
            <div class="flex1 g_bgcolor_key_grey">/</div>
            <div class="key_shift_right_width g_bgcolor_key_blue g_color_main">Shift</div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_key_blue g_color_main">Ctrl</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Win</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Alt</div>
            <div class="key_space_width g_bgcolor_main">Space</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Alt</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Win</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Fn</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Ctrl</div>
          </div>
        </div>
      </div>
      <div class="g_wid12"></div>
      <!--   键盘方向   -->
      <div class="key_dir flex_column">
        <!--   上   -->
        <div class="key_height flex border border_items_right_none">
          <div class="flex1 g_bgcolor_main">PrtSc</div>
          <div class="flex1 g_bgcolor_main">ScrLk</div>
          <div class="flex1 g_bgcolor_main">Pause</div>
        </div>
        <div class="g_wid12_h"></div>
        <!--   中   -->
        <div class="flex1 flex_column">
          <div class="flex1 flex border border_items_right_none  border_items_bottom_none">
            <div class="flex1 g_bgcolor_key_grey">Ins</div>
            <div class="flex1 g_bgcolor_key_grey">Home</div>
            <div class="flex1 g_bgcolor_key_grey">PgUp</div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_key_grey">Del</div>
            <div class="flex1 g_bgcolor_key_grey">End</div>
            <div class="flex1 g_bgcolor_key_grey">Pgdn</div>
          </div>
        </div>
        <div class="key_height"></div>
        <!--   下   -->
        <div class="flex1 flex_column">
          <div class="flex1 flex border border_items_right_none  border_items_bottom_none">
            <div class="flex1 border_top_none border_left_none"></div>
            <div class="flex1 g_bgcolor_main">↑</div>
            <div class="flex1 border_top_none border_right_none"></div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_main">←</div>
            <div class="flex1 g_bgcolor_main">↓</div>
            <div class="flex1 g_bgcolor_main">→</div>
          </div>
        </div>
      </div>
      <div class="g_wid12"></div>
      <!--   键盘数字   -->
      <div class="key_num flex_column">
        <!--   上   -->
        <div class="key_height flex border border_items_right_none">
          <div class="flex1 g_bgcolor_key_grey">🤣</div>
          <div class="flex1 g_bgcolor_key_grey">🤣</div>
          <div class="flex1 g_bgcolor_key_grey">🤣</div>
          <div class="flex1 g_bgcolor_key_grey">🤣</div>
        </div>
        <div class="g_wid12_h"></div>
        <!--   下   -->
        <div class="flex1 flex">
          <div class="flex3 flex_column">
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_blue g_color_main">Num</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main">/</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main">*</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey">7</div>
              <div class="flex1 g_bgcolor_key_grey">8</div>
              <div class="flex1 g_bgcolor_key_grey">9</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey">4</div>
              <div class="flex1 g_bgcolor_key_grey">5</div>
              <div class="flex1 g_bgcolor_key_grey">6</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey">1</div>
              <div class="flex1 g_bgcolor_key_grey">2</div>
              <div class="flex1 g_bgcolor_key_grey">3</div>
            </div>
            <div class="flex1 flex border border_items_right_none">
              <div class="flex2 g_bgcolor_key_blue g_color_main">0</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main">.</div>
            </div>
          </div>
          <div class="flex1 flex_column border">
            <div class="flex1 border_left_none border_bottom_none g_bgcolor_key_blue g_color_main">-</div>
            <div class="flex2 border_left_none border_bottom_none g_bgcolor_key_blue g_color_main">+</div>
            <div class="flex2 border_left_none g_bgcolor_key_blue g_color_main">Enter</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'KeyBoard',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.key_main{
  width: 1048px;
  height: 320px;
}
.key_dir{
  width: 138px;
}
.key_num{
  width: 184px;
}
.key_height{
  height: 48px;
}
.key_esc_width{
  width: 48px;
}
.key_f_width{
  width: 24px;
}
.key_backspace_width{
  width: 88px;
}
.key_tab_width{
  width: 64px;
}
.key_caps_width{
  width: 76px;
}
.key_shift_width,.key_enter_width{
  width: 98px;
}
.key_shift_right_width{
  width: 120px;
}
.key_space_width{
  width: 280px;
}
/*给每个键加入边框*/
.border>div:after{
  content: '';
  display: block;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  box-sizing: border-box;
  border: 1px solid var(--g_color_border);
}
.border>div.border_top_none:after{
  border-top: none;
}
.border>div{
  padding-top: 10px;
  font-weight: bold;
}
.border>div.border_left_none:after{
  border-left: none;
}

.border>div.border_bottom_none:after,
.border_items_bottom_none>div:after{
  border-bottom: none;
}
.border_items_right_none>div:not(:last-child):after,
.border>div.border_right_none:after{
  border-right: none;
}
</style>
