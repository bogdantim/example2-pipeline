def execs =[:]
for(int i=0;i<5;i++)
{
    def index=i
	execs[i] ={
		node {
			echo "executing for $index"
			sleep 10
		}
	}
}
execs.failFast=true
parallel execs