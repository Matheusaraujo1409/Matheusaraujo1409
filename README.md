class Queue
{
    public:
    Queue();  // Constructor
    ~Queue(); // Destrutor
    bool isEmpty() const;
    bool isFull() const;
    void print() const;

    void enqueue(ItemType);
    ItemType dequeue();
    private:
    int front;
    int back;
    ItemType* structure;

};
