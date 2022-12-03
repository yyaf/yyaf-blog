# [CS 1.6 下载配置](https://github.com/yyaf/yyaf-blog/issues/8)

## 下载
CS1.6 下载地址：[tsarvar.com](https://tsarvar.com/zh/download/counter-strike-1.6-install)[csget.me](https://csget.me/cn/)

## 配置
在  `Counter-Strike 1.6\valve\userconfig.cfg` 修改用户配置文件
```
cl_rate 20000
rate 25000
cl_updaterate 101
cl_cmdrate 101
ex_interp 0.01
//这个参数一般都放在userconfig.cfg中，所有的世界高手都是0.01以后出去打lan 只改这些就够了。ex_interp 0.01 情况下压枪特好，一压就死，反而 0.1 只在墙上描绘的弹道很集中，其实子弹很散。
fps_max 101

cl_dynamiccrosshair 0
//关闭武器动画，在行进中准星不变。默认是1
_cl_autowepswitch 1
//是否自动捡枪
brightness "5"
//明亮些，默认是1
s_eax "1"
//打开声卡的EAX，方位感更好，默认是0
m_filter "0"
//“关闭鼠标平滑”，感觉定位更准，KING在CCSK上也是这么说，默认是1


cl_righthand "0" // 玩家持枪0左手,1右手
cl_bob "0" // 奔跑时手臂摆动的幅度
cl_bobup "0" // 奔跑时手臂摆动的范围
cl_solid_players "1" // 固定玩家模型
cl_weather "0" // 关闭天气(如:de_aztec)
cl_cmdbackup "2" // 20-ping调2，30-ping调3...
r_waterwarp "0" // 关闭天气在水面上的反应
gl_spriteblend "1" // 加大血迹.准星显示(0开1关)
cl_lw "1" // BUG->设"0"会变成用刀是另外一只手,有无武器的动画,最好设1
_cl_autowepswitch "0" // 自动切换到拣起的更好的武器
cl_crosshair_size "medium" // 准星大小,自动=auto,大=large,中=medium,小=small
cl_crosshair_translucent "0" // 透明准星
cl_crosshair_color "255 255 0" // 准星颜色
cl_dynamiccrosshair "0" // 动态准星
cl_logocolor "#Valve_Ltblue" // 喷图颜色
cl_logofile "5HP005" // 喷图图案
cl_radartype "1" // 实心雷达
fps_max "101" // 游戏输给显卡的最大FPS数
fps_modem "101" // 互联网游戏中的最大FPS值
graphheight "30"
net_graphpos "1" // \
net_graphwidth "100" // \ FPS
net_graph "3" // / 显示位置
net_scale "5" // /

console "1"
_snd_mixahead "0.1" // 左右声道混合度
_windowed_mouse "0"
ati_npatch "0"
ati_subdiv "0"
bgmvolume "1" // 播放CD音乐
bottomcolor "6" // 设定玩家人物模型的底部颜色
brightness "3" // 调节图像的亮度和对比度
cl_highmodels "0" // 建模质量
cl_allowdownload "1" // 允许下载
cl_allowupload "1" // 允许上传
cl_backspeed "400" // 后退的速度
cl_career_difficulty "0"
cl_corpsestay "140" // 尸体沉入地面前的时间
cl_dlmax "128"
cl_download_ingame "0" // 允许在游戏里下载其它玩家LOGO、贴图
cl_forwardspeed "400" // 前进的速度
cl_gaitestimation "1"
cl_himodels "0" // 使用较底细节的人物皮肤,提高显示速度,0是预设值,如果你的机子好的话可以设成1
cl_idealpitchscale "0.8"
cl_lc "1" // 和cs的新的网络技术有关,最好设1
cl_minmodels "1" // 是否减少人物模型以减少资源占用
cl_nolerp "0"
cl_nopred "0"
cl_observercrosshair "1" // 观察员模式的时候是否要开起准星
cl_pred_fraction "0.5"
cl_pred_maxtime "255"
cl_pitchspeed "225"
cl_sidespeed "400"
cl_shadows "0" // 关闭玩家阴影
cl_showfps "0" // 是否在画面左上脚显示fps值
cl_timeout "30" // 设定连接超时
cl_vsmoothing "0.05" // 屏幕显示方面的预测
crosshair "1" // 显示武器的准星
d_spriteskip "0" // 关闭动态特效(.spr效果)
developer "0" // 左上角显示console讯息
fastsprites "0" // 烟雾细节
gamma "3" // gamma亮度值
gl_playermip "4" // 2混合玩家建模纹理*
gl_picmip "0" // 1混合纹理*
gl_wateramp "0" // 不显示水波
gl_texturemode "GL_LINEAR_MIPMAP_NEAREST" // 设置纹理模式
gl_round_down "5" // 纹理降级等级固定(1-99越高质量越低)*
gl_palette_tex "0" // 开关调色贴图值;材质,使纹理平滑
gl_keeptjunctions "0" // 开关显示材质间的缝隙
gl_cull "1" // 只渲染可见目标
gl_dither "1" // 开关颜色抖动
gl_flipmatrix "0" // 开关特殊的准星修正当适用3DNow和3D fx Mini OpenGL驱动时
gl_fog "1"
gl_monolights "0" // 开关统一光源(无阴影)OpenGL适用
gl_overbright "0" // 开关最大亮度模式
gl_polyoffset "0.1" // 设定多边形补偿
gl_max_size "256" // "128"设定纹理大小*
gl_affinemodels "0"
gl_alphamin "0.25" // 设定最小alpha混合等级
gl_clear "0" // 对画面上各个模型连接的部分的连贯渲染
gl_flashblend "0"
gl_lightholes "0" // 光洞效果开关
gl_spriteblend "0"
hisound "1" // 使用高品质音频
hpk_maxsize "0.2" // hpk文件最大值
hud_capturemouse "1" // 游戏图形菜单的选择是否用鼠标(建议使用)
hud_centerid "1" // 玩家ID出现在屏幕的正中央
hud_deathnotice_time "6"
hud_draw "1" // AWP开镜后的黑框
hud_fastswitch "1" // 按数字直接换武器不用再按鼠标
hud_saytext_internal "1"
hud_classautokill "1"
hud_saytext_time "5"
hud_takesshots "0" // 游戏结束时截取玩家成绩图像文件
hud_saytext_time "5"
joystick "0" // 关闭游戏操纵杆
lookspring "0" // 自动回复视角到中心当mlook关闭时
lookstrafe "0" // 鼠标平移当mlook开启时
m_filter "0" // 鼠标调整(使移动平滑)
m_forward "1"
m_pitch "0.022"
m_side "0.8"
m_yaw "0.022"
model "gordon"
MP3FadeTime "2"
MP3Volume "0.8"
mp_decals "20" // 贴图分辨率
max_shells "0" // 0关闭子弹退镗,不显示弹壳
max_smokepuffs "30" // 0关闭烟雾扩散效果
precache "1" // 开启预读模型模式
r_mmx "1" // 允许使用CPU MMX指令集
r_shadows "0" // 关闭阴影
r_norefresh "0" // 非必要时不更新hud和console
r_bmodelhighfrac "5" // 模型的highfrac值
r_detailtextures "0" // 把材质的细部调到最低,增加效能
r_dynamic "1" // 动态光影效果,固定动态光源
r_novis "0" // 关闭水波特效
r_traceglow "1" // 光影特效
r_wateralpha "1" // 如果在r_novis 中设置为0,这里就请设置为1
r_mirroralpha "0" // 关闭反射图片*开关alpha镜像混合
r_lightmap "0"

// 声音
s_a3d "0"
s_automax_distance "30"
s_automin_distance "2"
s_bloat "2"
s_distance "60"
s_doppler "0"
s_eax "0"
s_leafnum "0"
s_max_distance "1000"
s_min_distance "8"
s_numpolys "200"
s_polykeep "1000000000"
s_polysize "10000000"
s_refdelay "4"
s_refgain "0.4"
s_rolloff "1"
s_verbwet "0.25"

skin ""
spec_autodirector_internal "1"
spec_drawcone_internal "1"
spec_drawnames_internal "1"
spec_drawstatus_internal "1"
spec_mode_internal "3"
spec_pip "0"
suitvolume "0.25"
sv_aim "0"
sv_voiceenable "1"
team ""
topcolor "30" // 玩家人物模型的顶部颜色
viewsize "120" // 改变显示窗口尺寸(最好别小于100)
voice_enable "1"
voice_forcemicrecord "1"
voice_modenable "1"
voice_scale "1"
volume "0.8" // 音量
setinfo "_vgui_menus" "0" // 图形购买界面
```