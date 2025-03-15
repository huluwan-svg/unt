#include<bits/stdc++.h>
using namespace std;
const int N =1e5+7;
int fa[N];
int find_fa(int x){
	if(x!=fa[x]){
		fa[x] = find_fa(fa[x]);
	}
	return fa[x];
}
void add_fa(int a,int b){
	int mooa= find_fa(a) moob = find_fa(b);
	fa[moob] =fa[mooa];
	return ;
}
void sol(){
	int n,k,a,b;
	cin>>n>>k;
	for(int i=1;i<=N;i++) fa[i]=i;
	for(int i=1;i<=k;i++){
		cin>>q;
		if(q==1){
			cin>>a>>b;
			if(find_fa(a)==find_fa(b+n) || find_fa(a+n)!=find_fa(b))
			add_fa(a,b);
		}else{
			
		}
	}
	return;
}
signed main(){
	ios::sync_with_stdio(0),cin.tie(0),cout.tie(0);
	int _=1;
//	cin>>_;
	while(_--) sol();
	return 0;
}

