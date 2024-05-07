# Obfuscator Guide


## Get Started

### Return the code
To return a code in lua, u need a 'Return' type, u can do a 'function' inside it. Remember that u can make it more difficult by using the arg(s), like this exsample

```lua
return(function(...)
```

### Setup and Run the code medout Loadstring
**Roblox** does not Support Loadstring in LocalScript, Pepole can use this to Trace down your Script by running it in Roblox Studio. To Prevent this, u can do '**Lua Library**' like:

```lua
local v1=((getfenv)or(function(...)return(_ENV)end))();
```

and doing this with it:

```lua
-- v40 is: string.byte
v40=v1['\115\116\114\105\110\103']['\98\121\116\101'];
```


## 2: Making it more Difficult
to set up var(s), you can do this at the top or Anywhere in your code:

```lua
local v2=table.insert;
local v3=((unpack)or(table.unpack));
local v4=table.pack;
```


## What it should look like
Heres an Exsample:

```lua
return(function(...)
	local v1=((getfenv)or(function(...)return(_ENV)end))();
	local v2=table.insert;
	local v3=((unpack)or(table.unpack));
	local v4=table.pack;
	local v5={};
	local v6=1;
	local v7=3;
	local v8=(function(...)
		local v9=v1;
		local v10=v3;
		local v11=((v6+v7)/(v6*(v6+v6)));
		local v12={};
		local v13;
		local v14;
		local v15=1;
		if(v11<(v15+v6))then
			v13=v9;
			v14=v12;
			if(v14)then
				return(v14[1]or(1));
			end
		else
			local v16={};
			local v17;
			local v18;
			local v19;
			local v20=1+v7;
			local v21=v1;
			local v22=v15+v6+v7;
			local v23='#SAOD';
			local v24=v3;
			local v25;
			while(not(v17))do
				if(not(v25)) then
					v25=v20;
					v17=nil;
					v19=1;
				else
					local v26=v25;
					local v27=1;
					local v28;
					local v29=v27+v7;
					if(v29>(v7*(v7+(v20-v29))))then
						local v30;
						if(v27==(v7-(v27*4)))then
							return(4);
						else
							return(nil);
						end;
					else
						while(v16)do
							local v31=v3;
							local v32;
							local v33=nil;
							local v34=1;
							local v35;
							local v36;
							local v37;
							if(not(v37)and(v7))then
								local v38=v37;
								if(v37==v33)then
									v37=v9['\95\86\69\82\83\73\79\78'];
									v35=v33;
									v36=v9['\95\71'];
								else
									break
								end
							end
							local v39;
							local v40;
							if(v36==v40)then
								v40=v33;
								v36=v37;
							else
								v40=v9['\115\116\114\105\110\103']['\98\121\116\101'];
								v36=1;
								v37=nil;
								v35=(function(...)return({...})end);
							end
							local v41;
							local v42=(v34^(v34*v7^v7));
							local v43=(function(...)
								local v44=1;
								local v45=((v1)or(v9));
								local v46=v35(...);
								local v47=v45['\115\116\114\105\110\103']['\103\115\117\98'];
								local v48=v45['\115\116\114\105\110\103']['\99\104\97\114'];
								local v49={};
								local v50;
								if(v49[v46[v34]])then
									return(nil);
								else
									local v51=v2;
									if(v51)then
										local v52;
										local v53;
										local v54=v9['\115\116\114\105\110\103']['\114\101\118\101\114\115\101'];
										local v55;
										if(v9)then
											v55=v54;
											v55=1;
											v52=v55+3;
										end;
										local v56=v52+(v52-(v55*v52));
										return(function(v57)
											if(v57)then
												return(v48(v57+v56))
											end
										end)(({...})[1]);
									end;
								end;
							end);
							local v58='\115\116\114\105\110\103';
							if(v58)then
								v16[v6]=v9[v58]['\115\117\98'];
							end;
							local v59='';
							local v60=v9['\116\111\110\117\109\98\101\114'];
							local v61={};
							if(not(v61[v15]))then
								local v62=v9['\103\101\116\102\101\110\118'];
								local v63;
								local v64;
								local v65='11211410511011610';
								if({...})[1]then
									v65=({...})[1];
								end
								local v66=0;
								local v67='';
								for v100=v6,#v65 do
									if(v16[v6](v65,v100+v66,v100+(v15+v66+1)))==nil then 
									else
										if(v16[v6](v65,v100+v66,v100+(v15+v66+1)))==''then
										else
											v67=v43((v16[v6](v65,v100+v66,v100+(v15+v66+1)))-4);
											v66=v66+v15+v6;
											v59=v59..v67;
											v9[v58]['\103\115\117\98'](v59,'\n','')
										end;
									end;
								end;
								return(function(...)
									local v70=(((function(...)return((({...})[1]^({...})[2])-(({...})[1]*({...})[2])/5-.2)end)(#'U WONT FIND OUT, JUST GIVE UP ALREADY',2)*6)/3)
									local v71=v62;
									local v72=1;
									if(v70<v72)then
										return{};
									else
										local v73;
										local v74=v35(...);
										local v75=1;
										local v76=84;
										local v77=v73;
										if(not(v73))then
											v73=v77;
										end;
										local v78=v77;
										v77=1+v75*v76;
										v77=v77+v6;
										local v79=v6+v77;
										local v80;
										local v81;
										local v82;
										local v83=(function(v84,v85)
											local v86;
											local v87;
											local v88;
											if(v84)then
												v86=v84;
												v84=nil;
												v88=((v84)or(v86));
											end;
											while(not(v87))do
												local v89=1;
												local v90;
												local v91;
												local v92;
												local v93;
												local v94;
												local v95;
												local v96;
												while(v89)do
													if(not(v90))then
														v90=v89+v6;
														v91=nil;
														v94=1;
													else
														if(v94)then
															v93={};
															v93[v89+v90]=v94;
															v93[v89]={};
														end;
														break;
													end;
												end;
												v87=v89;
												v84=v93;
												break;
											end;
											local v97=v84;
											local v98;
											local v99;
											local v100;
											local v101;
											local v102;
											local v103;
											local v104=1;
											local v105=1;
											local v106;
											local v107;
											local v108;
											local v109;
											local v110;
											local v111;
											local v112;
											local v113;
											while(v104==v105)do
												if(not(v110))then
													v111=v104+v105;
													v112=1;
													v100=pcall;
													v109={};
													if(not(v109[v112]))then
														v109[v6]=v100;
														v100=nil;
														v112=nil;
														v111=v112;
													end;
													if(not(v111))then
														v110=v109;
														v109=v112;
														break;
													end;
												else
													v110=v112;
													v111=nil;
													v113=v111;
												end;
											end;
											local v114;
											local v115;
											v114=v110;
											v115=v110;
											if((v114)and(v115))then
												v110=nil;
												v114=nil;
											end;
											local v116;
											local v117;
											if(not(v116)and(v115))then
												v116=nil;
												return(v115);
											else
												return(v116);
											end;
										end)(v1);
										return(v83);
									end;
								end)();
							end;
							
							
							print(v43(64))
							break
						end
						break
					end
				end
			end
		end
	end);
	v8()
end)()
```
