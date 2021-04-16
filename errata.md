# Errata for *C++20 Quick Syntax Reference*

On **pages 96-97** [Code]:
 
class Shape {
public:
   virtual int getArea()=0; // not double, as Rectangle overrides as int
}

....

int main() {
   Rectangle r;
   printArea(r); // arg 'r' was missing
}

***

On **page xx** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

***
