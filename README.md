# assignment2-mamidi
# karthik reddy mamidi
### maldives

**Maldives**, in full **Republic of Maldives**, also called Maldive Islands, independent island country in the north-central Indian Ocean. It consists of a chain of about 1,200 small coral islands and sandbanks (some 200 of which are inhabited), grouped in clusters, or atolls.

---

### directions to maldives


1. go to kansas city airport
    1. Walk to the bustop
    2. travel by bus to the airport
2. travel to DFW airport
3. travel to maldives

* Camera
* Food
   * Biscuits
   * chocolates
   * chips
* clothes

### AboutMe

[AboutMe](https://github.com/Karthik143073/assignment2-mamidi/blob/main/AboutMe.md)

-----

### Table

I have buyed all the food items which was requied for me and the most preffered by me. The food includes the ice cream, salads, veggies and burgers which are bought from recommended stores. The detailed information about the food is listed below. 



|  food           |   location   |   price   |
|-----------------|------------------------- |
| butterscotch    |   walmart    |  $8.99    |
| salads          |   walmart    |  $9.00    |
| veggetables     |   hyvee      |  $25.00   |
| burgers         |   mcdonalds  |  $7.00    |

------
### Pithy quotes

>  “The purpose of our lives is to be happy.”  - *Benjemen*

>  “Life is not a problem to be solved, but a reality to be experienced.” - *David*

------

### Code fencing

>  Geometry (from the Ancient Greek: γεωμετρία; geo- "earth", -metron "measurement") is, with arithmetic, one of the oldest branches of mathematics. It is concerned with properties of space that are related with distance, shape, size, and relative position of figures.[1] A mathematician who works in the field of geometry is called a geometer.

For more information go to the link :<https://en.wikipedia.org/wiki/Geometry>





```
struct point2d {
    ftype x, y;
    point2d() {}
    point2d(ftype x, ftype y): x(x), y(y) {}
    point2d& operator+=(const point2d &t) {
        x += t.x;
        y += t.y;
        return *this;
    }
    point2d& operator-=(const point2d &t) {
        x -= t.x;
        y -= t.y;
        return *this;
    }
    point2d& operator*=(ftype t) {
        x *= t;
        y *= t;
        return *this;
    }
    point2d& operator/=(ftype t) {
        x /= t;
        y /= t;
        return *this;
    }
    point2d operator+(const point2d &t) const {
        return point2d(*this) += t;
    }
    point2d operator-(const point2d &t) const {
        return point2d(*this) -= t;
    }
    point2d operator*(ftype t) const {
        return point2d(*this) *= t;
    }
    point2d operator/(ftype t) const {
        return point2d(*this) /= t;
    }
};
point2d operator*(ftype a, point2d b) {
    return b * a;
}

```

For more information : <https://cp-algorithms.com/geometry/basic-geometry.html>









