<pre>
typedef struct node{		//스택안의 노드와 스택의 구조 
	void* data_ptr;
	struct node* link;
}STACK_NODE;

typedef struct{
	int count;
	STACK_NODE* top;
}STACK;

이 노드와 스택을 이용하여 스택을 생성하고 노드를 삽입, 제거하는 함수를 
