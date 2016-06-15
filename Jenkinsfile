node {
	// This will allocate a "default" workspace.
	writeFile file: "workspace_1st_node_block.txt", text: "${pwd()}"
}

node {
	// I think this *should* create another workspace, but it doens't, it reuses the 1st workspace.
	writeFile file: "workspace_2nd_node_block.txt", text: "${pwd()}"
}

node { ws { 
	writeFile file: "workspace_subworkspace.txt", text: "${pwd()}"
}}
