# posistcode
class node
{
	public:
		int nodeNumber;
		string nodeId;
		string referenceNodeId;
		string genesisReferenceNodeId;
		string hashValue;
		string data;
	node(int value)
	{
		node *newnode =new node;
		newnode->data = value;
		}	
		
}
string fucHash(int id,float value,string name)
{
	
}
int main()
{
	float value;
	cout<<"enter value of node";
	cin>>value;
	
	int id;
	cout<<"enter owner id";
	cin>>id;
	
	string name ;
	cout<<"enter owner name";
	gets(name);
	
	string data = fucHash(id,value,name);
	node *genesis = new node(data);
	
	
}
