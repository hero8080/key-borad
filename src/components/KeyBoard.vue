<template>
  <div class="g_full_screen flex_content_center g_bgcolor_bg">
    <div ref="key_board_style"></div>
    <div
        @keydown="keydown"
        tabindex="1"
        @keyup="keyup"
        ref="key_board"
        class="key_main g_bgcolor_key_bg flex g_pad12 g_radius4 text_center">
      <!--   键盘左侧   -->
      <div class="key_left flex1 flex_column">
        <!--   上   -->
        <div class="key_height flex border border_items_right_none">
          <div class="flex1 g_bgcolor_main key_27">Esc</div>
          <div class="key_esc_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_key_grey key_112">F1</div>
          <div class="flex1 g_bgcolor_key_grey key_113">F2</div>
          <div class="flex1 g_bgcolor_key_grey key_114">F3</div>
          <div class="flex1 g_bgcolor_key_grey key_115">F4</div>
          <div class="key_f_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_main key_116">F5</div>
          <div class="flex1 g_bgcolor_main key_117">F6</div>
          <div class="flex1 g_bgcolor_main key_118">F7</div>
          <div class="flex1 g_bgcolor_main key_119">F8</div>
          <div class="key_f_width border_top_none border_bottom_none"></div>
          <div class="flex1 g_bgcolor_key_grey key_120">F9</div>
          <div class="flex1 g_bgcolor_key_grey key_121">F10</div>
          <div class="flex1 g_bgcolor_key_grey key_122">F11</div>
          <div class="flex1 g_bgcolor_key_grey key_123">F12</div>

        </div>
        <div class="g_wid12_h"></div>
        <!--   下   -->
        <div class="flex1 flex_column">
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="flex1 g_bgcolor_key_blue g_color_main key_192">~</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_49">1</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_50">2</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_51">3</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_52">4</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_53">5</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_54">6</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_55">7</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_56">8</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_57">9</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_48">0</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_189">-</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_187">+</div>
            <div class="key_backspace_width g_bgcolor_key_blue g_color_main key_8">Backspace</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_tab_width g_bgcolor_key_blue g_color_main key_9">Tab</div>
            <div class="flex1 g_bgcolor_key_grey key_81">Q</div>
            <div class="flex1 g_bgcolor_key_grey key_87">W</div>
            <div class="flex1 g_bgcolor_key_grey key_69">E</div>
            <div class="flex1 g_bgcolor_key_grey key_82">R</div>
            <div class="flex1 g_bgcolor_key_grey key_84">T</div>
            <div class="flex1 g_bgcolor_key_grey key_89">Y</div>
            <div class="flex1 g_bgcolor_key_grey key_85">U</div>
            <div class="flex1 g_bgcolor_key_grey key_73">I</div>
            <div class="flex1 g_bgcolor_key_grey key_79">O</div>
            <div class="flex1 g_bgcolor_key_grey key_80">P</div>
            <div class="flex1 g_bgcolor_key_grey key_219">[</div>
            <div class="flex1 g_bgcolor_key_grey key_221">]</div>
            <div class="key_tab_width g_bgcolor_key_blue g_color_main key_220">\|</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_caps_width g_bgcolor_key_blue g_color_main key_20">Caps</div>
            <div class="flex1 g_bgcolor_key_grey key_65">A</div>
            <div class="flex1 g_bgcolor_key_grey key_83">S</div>
            <div class="flex1 g_bgcolor_key_grey key_68">D</div>
            <div class="flex1 g_bgcolor_key_grey key_70">F</div>
            <div class="flex1 g_bgcolor_key_grey key_71">G</div>
            <div class="flex1 g_bgcolor_key_grey key_72">H</div>
            <div class="flex1 g_bgcolor_key_grey key_74">J</div>
            <div class="flex1 g_bgcolor_key_grey key_75">K</div>
            <div class="flex1 g_bgcolor_key_grey key_76">L</div>
            <div class="flex1 g_bgcolor_key_grey key_186">;</div>
            <div class="flex1 g_bgcolor_key_grey key_222">"</div>
            <div class="key_enter_width g_bgcolor_key_blue g_color_main key_13">Enter</div>
          </div>
          <div class="flex1 flex border border_items_right_none border_items_bottom_none">
            <div class="key_shift_width g_bgcolor_key_blue g_color_main key_16">Shift</div>
            <div class="flex1 g_bgcolor_key_grey key_90">Z</div>
            <div class="flex1 g_bgcolor_key_grey key_88">X</div>
            <div class="flex1 g_bgcolor_key_grey key_67">C</div>
            <div class="flex1 g_bgcolor_key_grey key_86">V</div>
            <div class="flex1 g_bgcolor_key_grey key_66">B</div>
            <div class="flex1 g_bgcolor_key_grey key_78">N</div>
            <div class="flex1 g_bgcolor_key_grey key_77">M</div>
            <div class="flex1 g_bgcolor_key_grey key_188">,</div>
            <div class="flex1 g_bgcolor_key_grey key_190">.</div>
            <div class="flex1 g_bgcolor_key_grey key_181">/</div>
            <div class="key_shift_right_width g_bgcolor_key_blue g_color_main key_16">Shift</div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_key_blue g_color_main key_17">Ctrl</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_91">Win</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_18">Alt</div>
            <div class="key_space_width g_bgcolor_main key_32">Space</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_18">Alt</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_91">Win</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main">Fn</div>
            <div class="flex1 g_bgcolor_key_blue g_color_main key_17">Ctrl</div>
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
            <div class="flex1 g_bgcolor_key_grey key_45">Ins</div>
            <div class="flex1 g_bgcolor_key_grey key_36">Home</div>
            <div class="flex1 g_bgcolor_key_grey key_33">PgUp</div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_key_grey key_45">Del</div>
            <div class="flex1 g_bgcolor_key_grey key_34">End</div>
            <div class="flex1 g_bgcolor_key_grey key_18">Pgdn</div>
          </div>
        </div>
        <div class="key_height"></div>
        <!--   下   -->
        <div class="flex1 flex_column">
          <div class="flex1 flex border border_items_right_none  border_items_bottom_none">
            <div class="flex1 border_top_none border_left_none"></div>
            <div class="flex1 g_bgcolor_main key_38">↑</div>
            <div class="flex1 border_top_none border_right_none"></div>
          </div>
          <div class="flex1 flex border border_items_right_none">
            <div class="flex1 g_bgcolor_main key_37">←</div>
            <div class="flex1 g_bgcolor_main key_40">↓</div>
            <div class="flex1 g_bgcolor_main key_39">→</div>
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
              <div class="flex1 g_bgcolor_key_blue g_color_main key_144">Num</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main key_111">/</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main key_106">*</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey key_103">7</div>
              <div class="flex1 g_bgcolor_key_grey key_104">8</div>
              <div class="flex1 g_bgcolor_key_grey key_105">9</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey key_100">4</div>
              <div class="flex1 g_bgcolor_key_grey key_101">5</div>
              <div class="flex1 g_bgcolor_key_grey key_102">6</div>
            </div>
            <div class="flex1 flex border border_items_right_none border_items_bottom_none">
              <div class="flex1 g_bgcolor_key_grey key_97">1</div>
              <div class="flex1 g_bgcolor_key_grey key_98">2</div>
              <div class="flex1 g_bgcolor_key_grey key_99">3</div>
            </div>
            <div class="flex1 flex border border_items_right_none">
              <div class="flex2 g_bgcolor_key_blue g_color_main key_96">0</div>
              <div class="flex1 g_bgcolor_key_blue g_color_main key_110">.</div>
            </div>
          </div>
          <div class="flex1 flex_column border">
            <div class="flex1 border_left_none border_bottom_none g_bgcolor_key_blue g_color_main key_109">-</div>
            <div class="flex2 border_left_none border_bottom_none g_bgcolor_key_blue g_color_main key_107">+</div>
            <div class="flex2 border_left_none g_bgcolor_key_blue g_color_main key_18">Enter</div>
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
  },
  mounted() {
    this.$refs.key_board.focus()
  },
  methods:{
    keydown(e){
      e.preventDefault()
      let keyCode=e.keyCode
      console.log(e.key+':'+keyCode)
      this.$refs.key_board_style.innerHTML=
          `
          <style>
            .key_${keyCode}{
                background-color: dodgerblue;
            }
          </style>
          `
    },
    keyup(){
      this.$refs.key_board_style.innerHTML=''
    }
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
