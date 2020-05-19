# Project Plan

- **Student's Name** - Parth Shandilya
- **Mentor** - Sean Grady

## Project Description

The Zowe Virtual Desktop has different plugins and each plugin has its own documentation. Main goal of the project is to implement a documentation viewer application and make it ready to be added in the API catalog. Plugins may have a variety of documentation that are shipped with them: readme, licenses, guides, api documentation and more. As the various types of documentation generally resides in file formats that browsers can visualize, be it PDF or text or markdown, it would be convenient to present this documentation in the same place where the plugins run. A standard viewer & standard packaging scheme is needed so that plugin developers do not instead come up with their own way to solve the same problem, multiple times.

## Deliverables

A new default web application will enable users to view text & pdf documents bundled into plugins. This viewer can be invoked via the Desktop’s App2App communication scheme so that it can be popped up on-demand by the plugin, or opened directly by the user for them to be able to drill-down to each plugin & each documentation file.

## Coding Plan

| Week	| Description of activities                                                                                        	| Goal                                                                                                                     	|
|----------	|------------------------------------------------------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------------	|
| 1   	| Communicate with the team and understand the project description.                                                	| Get familiar with the Zowe app framework.                                                                                	|
| 2   	| Set up the zowe dev environment.                                                                                 	| Will help to understand how plugins work.                                                                                	|
| 3   	| Research for the best libraries to display documentation of various formats.                                     	| Find the libraries that are popular and maintained that can be used in the project.                                      	|
| 4   	| Research for the best libraries to display documentation of various formats.                                     	| Find the libraries that are popular and maintained that can be used in the project.                                      	|
| 5   	| Finalize the libraries.                                                                                          	| Share the finalized solution with the team.                                                                              	|
| 6   	| Start working on Proof of Concept for the application.                                                            	| Share the proof of concept with the team.                                                                                	|
| 7   	| Start working on the new application with node and express which displays available plugins.                     	| API to show available plugins.                                                                                           	|
| 8   	| Check for Bugs and work on any feedback from the mentor.                                                         	| Finalize the API to show available plugins.                                                                              	|
| 9   	| Work on extending the API to show the file structure of each plugin when explored.                               	| Plugin display API completed with required functionalities of exploring every plugin containing different documentation. 	|
| 10  	| Work on showing markdown format with finalized library.                                                          	| Functionality to show markdown format.                                                                                   	|
| 11  	| Check for Bugs and work on any feedback from the mentor.                                                         	| Markdown display completed with required functionalities.                                                                	|
| 12  	| Work on rendering PDF format with finalized library                                                              	| Functionality to show PDF Format.                                                                                        	|
| 13  	| Check for Bugs and work on any feedback from the mentor.                                                         	| PDF display completed with required functionalities.                                                                     	|
| 14  	| Work on showing Swagger API JSON in readable format or discuss the possibilities of getting it from API catalog  	| Functionality to show Swagger API documentation                                                                          	|
| 15  	| Check for Bugs and work on any feedback from the mentor.                                                         	| Swagger API JSON display with required functionalities.                                                                  	|
| 16  	| Start working file-api. Work on the replace function.                                                            	| Finalized replace api with unit tests.                                                                                   	|
| 17  	| Start working on the copy file-api.                                                                              	| Finalized copy-file api with unit tests.                                                                                 	|
| 18  	| Finalize all the APIs and add tests wherever required.                                                           	| Finalized application with unit tests.                                                                                   	|
| 19  	| Testing. Getting feedback on bugs. Start working on the documentation                                            	| Finalized documentation. Work on final evaluations, feedback and bugs reported.                                          	|
| 20  	| Work on the guides and video.                                                                                    	| Finalized video and guides of the project.                                                                               	|