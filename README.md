1, Under ubuntu, after libsoil-dev is installed, you still need to download SOIL source code and when you compile:
   g++ -o main *.cpp -lGL -lGLU -lglut -lGLEW -I /path_to_SOIL_include
  
2, If some source code can't be compiled owing to some core dump stuffs, find CHECK_ERROR macros near the problematic 
  place, comment it may help
  
