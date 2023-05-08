This project builds a java code by Jenkins (END TO END DECLARATIVE FILE)
						 --> Sonar analysis 
							--> Sonar quality gate check  
						   	 	--> builds & Push docker image  
								 	--> update k8 manifest 
							    	 		--> deploys container to k8 kluster via argo cd
