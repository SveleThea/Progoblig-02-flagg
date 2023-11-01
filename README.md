# Progoblig-02-flagg
fun flag(country) :
  if (country == "norway"):
    (overlay-xy(rectangle(220, 20, "solid", "midnightblue"), -0, -70,
        overlay-xy(rectangle(20, 160, "solid", "midnightblue"), -70, -0, 
          overlay-xy(rectangle(220, 40, "solid", "white"), -0, -60, 
            overlay-xy(rectangle(40, 160, "solid", "white"), -60, -0,
              rectangle(220, 160, "solid", "firebrick"))))))
    
  else if (country == "sweden"):
    (overlay-xy(rectangle(220, 30, "solid", "gold"), -0, -65, 
        overlay-xy(rectangle(30, 160, "solid", "gold"), -80, -0,
          rectangle(220, 160, "solid", "steel-blue"))))
    
  else if (country == "denmark"):
    (overlay-xy(rectangle(370, 40, "solid", "white"), -0, -125,
        overlay-xy(rectangle(40, 280, "solid", "white"), -125, -0,
          rectangle(370, 280, "solid", "crimson"))))
    
  else if (country == "finland"):
    (overlay-xy(rectangle(180, 30, "solid", "midnightblue"), -0, -40,
        overlay-xy(rectangle(30, 110, "solid", "midnightblue"), -50, -0,
          rectangle(180, 110, "solid", "white"))))
    
  else if (country == "faroe-islands"):
    (overlay-xy(rectangle(220, 20, "solid", "crimson"), -0, -70,
        overlay-xy(rectangle(20, 160, "solid", "crimson"), -70, -0, 
          overlay-xy(rectangle(220, 40, "solid", "royal-blue"), -0, -60, 
            overlay-xy(rectangle(40, 160, "solid", "royal-blue"), -60, -0,
              rectangle(220, 160, "solid", "white"))))))
    
  else if (country == "iceland"):
    (overlay-xy(rectangle(250, 20, "solid", "crimson"), -0, -80,
        overlay-xy(rectangle(20, 180, "solid", "crimson"), -80, -0, 
          overlay-xy(rectangle(250, 40, "solid", "white"), -0, -70, 
            overlay-xy(rectangle(40, 180, "solid", "white"), -70, -0,
              rectangle(250, 180, "solid", "royal-blue"))))))
    
  else if (country == "aaland"):
    (overlay-xy(rectangle(270, 20, "solid", "crimson"), -0, -75,
        overlay-xy(rectangle(20, 170, "solid", "crimson"), -100, -0, 
          overlay-xy(rectangle(270, 50, "solid", "gold"), -0, -60, 
            overlay-xy(rectangle(50, 170, "solid", "gold"), -85, -0,
              rectangle(270, 170, "solid", "steel-blue"))))))
  end
end
