# Queue1
public class MyQueue<E> {
  public java.util.LinkedList<E> list = new java.util.LinkedList<>();
  
  public void enqueue(E e)
  {
     list.addLast(e);
  }
  
  public MyQueue (E[] e)
  {
  }
  
  public MyQueue() 
  {
  }
  
  public E dequeue()
  {
     return list.removeFirst();
  }
  
  public E getElement(int i)
  {
      return list.element();
  }
  
  public E peek()
  { 
      return list.removeFirst();
  }
  
  public int getSize()
  {
      return list.size();
  }
  
  public boolean isEmpty(E e)
  { 
      if (list == null
          return true;
      else
          return false;
   }
   
   @Override
   public String toString()
   {
       return "Queue: " + list.toString();
   }
 }
