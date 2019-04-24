# CC2-Problem-Set-3
Laboratorio A 

# Ejercicio 2.1

class Point
 {
 private :
 int x, y;

 public :
 Point (int u, int v) : x(u), y(v) {}
 int getX () { return x; }
 int getY () { return y; }
 void doubleVal ()
     {
        x *= 2;
        y *= 2;
     }
 };

 int main ()
 {
  Point myPoint (5, 3);
  myPoint . doubleVal ();
  cout << myPoint . getX () << " " << myPoint . getY () << "\n";
  return 0;
 }


# Ejercicio 2.2 

class Point
{
    private :
        int x, y;

    public :
        Point (int u, int v) : x(u), y(v) {}
        int getX () { return x; }
        int getY () { return y; }

        void setX (int newX ) { x = newX ; }
};

int main ()
{
    Point p(5, 3);
    p. setX (9001) ;
    cout << p. getX () << "  " << p. getY ();

    return 0;
}


# Ejercicio 2.3

class Point
{
    private :
        int x, y;

    public :
        Point (int u, int v) : x(u), y(v) {}
        int getX () { return x; }
        int getY () { return y; }
};

 int main ()
 {
    Point p(5, 3);
    cout << p.getX() << " " << p.getY() << "\n";
    return 0;
 }


# Ejercicio 2.4 

class Point
{
    private :
        int x, y;

    public :
        Point (int u, int v) : x(u), y(v) {}
        int getX () { return x; }

        void setX (int newX );
};

void Point::setX (int newX ){ x = newX ; }

int main ()
{
    Point p(5, 3);
    p. setX (0);
    cout << p. getX () << " " << "\n";
    return 0;
}


# Ejercicio 2.5

int main(){
      int tam ;
      cin >> tam ;
      int * nums = new int[ tam ];
         for(int i = 0; i < tam ; ++i)
         { 
            cin >> nums [i];
         }

      delete[] nums ;
}


# Ejercicio 2.6

class Point
{
    private :
        int x, y;

    public :
        Point (int u, int v) : x(u), y(v) {}
        int getX () { return x; }
        int getY () { return y; }
};

 int main ()
{
    Point *p = new Point (5, 3);

    cout << p-> getX () << " " << p-> getY ();
    delete p;
    return 0;
}


# Ejercicio 3 

# .header

class Point
{
    private :
        int x, y;

    public :
        Point (int u=0, int v=0) : x(u), y(v) {}
        int getX () { return x; }
        int getY () { return y; }

        void setX (int newX ) { x = newX ; }
        void setY (int newY ) { y = newY ; }
};

# .cpp

int main()
 {
     Point p(5,3);
     p.setY(5);
     cout<< p.getX()<< " " << p.getY();
 }
 
 
 # Ejercicio 4
 
