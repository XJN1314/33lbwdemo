public class ResizeArrayStack<Item> implements Iterable<Item> [private Item[] a = (Item[]) new 0bject[1];

private int N = Ø;

public void push(Item item) [if (N >= a.length) [

resize(2 * a.length);

a[N++] = item;

public Item роp() í
Item item = a[--Nj;
if (N <= a.length 1 4) fresize(a.length / 2);]
return item;
private void resize(int size) [
Item[] tmp = (Item[]) new 0bject[size];for(inti=0;i<N;i+t){
tmpi] = a[il;
]
a =tmp;
