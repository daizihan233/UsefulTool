# UsefulTool
def:
- bqbzz(openimg,size=30,rotate=0,color=(0,0,0),ttf=None,text="我\n真\n是\n个\n大\n聪\n明"):
  - oepnimg:OpenIMG(PNG,GIF,JPG,JPEG,BMP)
  - size:font size
  - rotate:font rotate
  - color:font color
  - ttf:Using TTF font
  - text:What do you want to write?
  - Can:Write something on a photo
- json_rw(filename,mode='r'):
  - filename:Oepn file
  - mode:How to open the file(r,w,r+,w+,rb,wb,ab,rb+,wb+,ab+)
  - Can:load a json file
- finder(lst):
  - lst:find a number in what?
  - Can:Find a number in a list
- IDNumber_Tool(idnum):
  - idnum:Your IDnumber in China
  - Can:Find info in your IDnumber in China(like:Your Gender,when you was born)
- tgt(x=0,y=0):
  - Let turtle move to(x,y)
- hundred_people_name():
  - Can:
    - Press your First Name into it
    - Print a list
 - summon_gif(gif_dir,sort_reverse=False,ext_file=[".png",".jpg",".jpeg",".bmp"],output_name="Deflut.gif",txt="",ttf="STXINGKA.TTF",text_xy=(80,600),size=80,ttf_color=(0,0,0),use_own_color_list=False,own_color_list=[(0,0,0)]):
  - gif_dir:Where are your imgs to summon a gif?
  - sort_reverse:Do you want to invert your gif?If you want,set this True.
  - ext_file:allowed file exts
  - output_name:Your gif's name
  - txt,ttf,size,ttf_color:Please look at [bqbzz]
  - use_own_color_list:If this porgram is using Multi-group-color-list,please set it True.
  -o wn_color_list: Multi-group-color-list
- gif_boom(myDir="renders",open_gif="bcm.gif")
  - myDir:Images will save at here.
  - open_gif:Which gif do you want to boom?
- init_turtle(x,y,c)
  - x,y:go to (x,y)
  - c:set pen_color and fill_color c
- os_star(x,y,l,c)
  - Can:Draw a five pointed star at (x,y)
  - long:l
  - color:c
  - Angle adjustment is not supported temporarily
