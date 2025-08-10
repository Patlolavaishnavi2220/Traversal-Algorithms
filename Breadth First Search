# adjacency list is given as input
adjlst=[[1,2],[0,3],[0],[1]]
class solution:
    def bfs(self,adjlst):
        v=len(adjlst)
        startNode=0
        visited=[0]*v
        queue=[]
        ans=[]
        if(visited[startNode]==0):
            visited[startNode]=1
            queue.append(startNode)
            while(len(queue)>0):
                popNode=queue.pop(0)
                for i in adjlst[popNode]:
                    if(visited[i]==0):
                        visited[i]=1
                        queue.append(i)
                ans.append(popNode)
            return ans
ob=solution()
print(ob.bfs(adjlst))
