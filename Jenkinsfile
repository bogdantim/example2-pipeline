def execs =[:]
for(int i=0;i<5;i++)
{
	execs[i] ={
		node {
			echo "executing for $i"
			sleep 10
		}
	}
}
execs.failFast=true
parallel execs