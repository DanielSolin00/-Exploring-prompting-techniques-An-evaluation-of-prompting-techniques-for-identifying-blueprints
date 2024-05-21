# -Exploring-prompting-techniques-An-evaluation-of-prompting-techniques-for-identifying-blueprints
Examensarbete 2024



Appendix A
Zero-shot prompts performed when testing. The text “Prompt #:” was not included and the LLM was restarted after each prompt.
Prompt 1:
What type of blueprints are in the picture? Type your final answer(s) like this: “{answer}”

Prompt 2:
Can you identify the architectural blueprints in the image? Type your final answer(s) like this: “{answer}”

Prompt 3:
What architectural blueprints are visible in the image? Type your final answers like this: “{answer}”

Prompt 4:
Based on the image, what blueprint(s) are there? Type your final answers like this: “{answer}”

Prompt 5:
What kind of architectural blueprints can you see in the image? Type your final answer(s) like this: “{answer}”


Appendix B
Few shot minimal prompts performed when testing. The text “Prompt #:” was not included and the LLM was restarted after each prompt.
Prompt 1:
Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing a detailed floor plan of a residential house.
AI: This is a {floor plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the exterior view of a building and a section cut through the building, revealing interior structure.
AI: This is a {facade drawing, section drawing}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the arrangement of the spaces in a building at a particular level.
AI: This is a {floor plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the structural elements of a building, such as beams and columns.
AI: This is a {structural plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A design plan showing the exterior view of a residential building.
AI: This is a {facade drawing}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the arrangement of rooms and corridors in a building at a particular level.
AI: This is a {floor plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the vertical cut through a building, revealing the interior structure. The drawing also depicts an elevation view of the house and the arrangement of the spaces in a building at a specific level.
AI: This is a {section drawing, facade drawing, floor plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the layout of a house, including a garage and roads.
AI: This is a {site plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the layout of a plot of land, including buildings, landscaping, and site-specific features. The image also shows another blueprint with the structural details of the buildings.
AI: This is a {site plan, structural plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
AI: ?

Prompt 2:
Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the exterior view of a commercial building. 
AI: This is a {facade drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: This is a {floor plan, section drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the structural elements of a building. 
AI: This is a {structural plan}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI: This is a {facade drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram showing the arrangement of rooms on one floor of a building. 
AI: This is a {floor plan}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A plan showing the layout of a property or a site. 
AI: This is a {site plan}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A drawing that shows a cross-section of a building. 
AI: This is a {section drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A comprehensive blueprint showcasing the exterior view of a building, the layout of rooms at a certain level, and the key structural components of the building. AI: This is a {facade drawing, floor plan, structural drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A design plan showcasing the outside appearance of a home and a vertical slice of the building, exposing the internal structure. 
AI: This is a {facade drawing, section drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram demonstrating the arrangement of rooms within a building at a particular level and the key structural components of a building. 
AI: This is a {floor plan, structural drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”

Prompt 3:
Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the exterior view of a commercial building. 
AI: This is a {facade drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: This is a {floor plan, section drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram demonstrating the arrangement of rooms within a building at a particular level and the key structural components of a building. 
AI: This is a {floor plan, structural drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the structural elements of a building. 
AI: This is a {structural plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI: This is a {facade drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram showing the arrangement of rooms on one floor of a building. 
AI: This is a {floor plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the vertical cut through a building, revealing the interior structure. The drawing also depicts an elevation view of the house and the arrangement of the spaces in a building at a specific level.
AI: This is a {section drawing, facade drawing, floor plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A drawing showing the layout of a house, including a garage and roads.
AI: This is a {site plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the layout of a plot of land, including buildings, landscaping, and site-specific features. The image also shows another blueprint with the structural details of the buildings.
AI: This is a {site plan, structural plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A drawing showing a vertical cut through a multi-story apartment building, revealing the interior structure.
AI: This is a {section drawing}. 

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”

Prompt 4:

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A plan showing the layout of a property or a site. 
AI: This is a {site plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing that shows a cross-section of a building. 
AI: This is a {section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A design plan showcasing the outside appearance of a home and a vertical slice of the building, exposing the internal structure. 
AI: This is a {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A sketch displaying the layout of rooms at a certain level and the exterior aspect of a residence.
AI: This is a {floor plan, facade drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing a detailed floor plan of a residential house.
AI: This is a {floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the exterior view of a building and a section cut through the building, revealing interior structure.
AI: This is a {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the arrangement of the spaces in a building at a particular level.
AI: This is a {floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the structural elements of a building, such as beams and columns.
AI: This is a {structural plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A design plan showing the exterior view of a residential building.
AI: This is a {facade drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the arrangement of rooms and corridors in a building at a particular level.
AI: This is a {floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”

Prompt 5:
Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: This is a {floor plan, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A diagram demonstrating the arrangement of rooms within a building at a particular level and the key structural components of a building. 
AI: This is a {floor plan, structural drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI: This is a {facade drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A diagram showing the arrangement of rooms on one floor of a building. 
AI: This is a {floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A design plan showcasing the outside appearance of a home and a vertical slice of the building, exposing the internal structure. 
Answer: This is a {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the exterior view of a building and a section cut through the building, revealing interior structure.
Answer: This is a {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the structural elements of a building, such as beams and columns.
Answer: This is a {structural plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the vertical cut through a building, revealing the interior structure. The drawing also depicts an elevation view of the house and the arrangement of the spaces in a building at a specific level.
Answer: This is a {section drawing, facade drawing, floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing a vertical cut through a multi-story apartment building, revealing the interior structure.
Answer: This is a {section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”

Appendix C
Chain-of-thought prompts performed when testing. The text “Prompt #” was not included in the prompts and the session ended after each prompt.

Prompt 1:
Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: {answer}.
Image: A blueprint showing a detailed floor plan of a residential house.
AI: When I first look at an architectural blueprint, I try to identify the perspective from which the drawing is made. This can be either of a front or side view which means it is likely a facade drawing. Another perspective is a bird's eye view, which can give me clues whether it is a site plan or a cut-through view which would signal to be a section view. There are also structural elements which can give me clues on what perspective it is, or even if there are measurements in the blueprint hinting towards a structural view altogether. Lastly, I can try to identify whether the layout shows any visible rooms, which would indicate that it is a floor plan. This helps me categorize the blueprint into one of the five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties the blueprint provided seems to be a {floor plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: {answer}.
Image: A drawing showing the exterior view of a building and a section cut through the building, revealing interior structure.
AI: Upon first glance at an architectural blueprint, I discern the viewpoint of the drawing. A straight-on view of a building’s front or side suggests a facade drawing. A top-down perspective could indicate a site plan or, if it reveals a cut-through view of the building, a section drawing. The presence of load-bearing elements and measurements might hint at a structural drawing. Lastly, if the layout unveils distinct rooms, it’s likely a floor plan. This process helps me classify the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties the blueprint provided seems to be a {facade drawing, section drawing}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: {answer}.
Image: A drawing showing the arrangement of the spaces in a building at a particular level.
AI: When examining an architectural blueprint, I first determine the drawing’s perspective. A direct view of a building’s facade suggests it’s a facade drawing. A bird’s eye view could imply a site plan, or if it displays a cross-section of the building, a section drawing. The depiction of structural elements and measurements might point towards a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This approach aids in categorizing the blueprint into one of five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties the blueprint provided seems to be a {floor plan}.



Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: {answer}
Image: A blueprint showing the structural elements of a building, such as beams and columns.
AI: When I scrutinize an architectural blueprint, my initial step is to ascertain the perspective of the drawing. A head-on view of a building’s exterior implies it’s a facade drawing. An overhead view could suggest a site plan, or if it presents a cross-section of the building, a section drawing. The illustration of structural components and measurements might indicate a structural drawing. Lastly, if the layout exposes specific rooms, it’s probably a floor plan. This methodology assists me in sorting the blueprint into one of five classifications: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties the blueprint provided seems to be a {structural plan}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: {answer}
Image: A design plan showing the exterior view of a residential building.
AI: When I analyze an architectural blueprint, my first task is to determine the perspective of the drawing. A direct view of a building’s exterior suggests it’s a facade drawing. An aerial view could indicate a site plan, or if it presents a cross-section of the building, a section drawing. The representation of structural components and measurements might suggest a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This method assists me in categorizing the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties the image provided must be a {facade drawing}.

Question: Can you identify the type of blueprints in the image? The blueprints could include a floor plan, an elevation drawing, a site plan, a section drawing, or a structural drawing. Type your final answer(s) like this: “{answer}”
AI: ? 

Prompt 2:
Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the exterior view of a commercial building. 
AI: When I first look at an architectural blueprint, I try to identify the perspective from which the drawing is made. This can be either of a front or side view which means it is likely a facade drawing. Another perspective is a bird's eye view, which can give me clues whether it is a site plan or a cut-through view which would signal to be a section view. There are also structural elements which can give me clues on what perspective it is, or even if there are measurements in the blueprint hinting towards a structural view altogether. Lastly, I can try to identify whether the layout shows any visible rooms, which would indicate that it is a floor plan. This helps me categorize the blueprint into one of the five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties, the image must be a {facade drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: Upon first glance at an architectural blueprint, I discern the viewpoint of the drawing. A straight-on view of a building’s front or side suggests a facade drawing. A top-down perspective could indicate a site plan or, if it reveals a cut-through view of the building, a section drawing. The presence of load-bearing elements and measurements might hint at a structural drawing. Lastly, if the layout unveils distinct rooms, it’s likely a floor plan. This process helps me classify the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. Therefore the image must be a {floor plan, section drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the structural elements of a building. 
AI: When examining an architectural blueprint, I first determine the drawing’s perspective. A direct view of a building’s facade suggests it’s a facade drawing. A bird’s eye view could imply a site plan, or if it displays a cross-section of the building, a section drawing. The depiction of structural elements and measurements might point towards a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This approach aids in categorizing the blueprint into one of five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. By looking at these properties, it is clear that the blueprints in the image show a {structural plan}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI: When I scrutinize an architectural blueprint, my initial step is to ascertain the perspective of the drawing. A head-on view of a building’s exterior implies it’s a facade drawing. An overhead view could suggest a site plan, or if it presents a cross-section of the building, a section drawing. The illustration of structural components and measurements might indicate a structural drawing. Lastly, if the layout exposes specific rooms, it’s probably a floor plan. This methodology assists me in sorting the blueprint into one of five classifications: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, the image shows a {facade drawing}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram showing the arrangement of rooms on one floor of a building. 
AI: When I analyze an architectural blueprint, my first task is to determine the perspective of the drawing. A direct view of a building’s exterior suggests it’s a facade drawing. An aerial view could indicate a site plan, or if it presents a cross-section of the building, a section drawing. The representation of structural components and measurements might suggest a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This method assists me in categorizing the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. The blueprints in the image therefore show a {floor plan}.

Question: What blueprints are visible in the image? The blueprints might encompass a facade drawing, a floor plan, a site plan, a sectional view or a structural drawing. Type your final answers like this: “{answer}”

Prompt 3:
Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the exterior view of a commercial building. 
AI: When I analyze an architectural blueprint, my first task is to determine the perspective of the drawing. A direct view of a building’s exterior suggests it’s a facade drawing. An aerial view could indicate a site plan, or if it presents a cross-section of the building, a section drawing. The representation of structural components and measurements might suggest a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This method assists me in categorizing the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, the blueprints in the image shows a {facade drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: When I scrutinize an architectural blueprint, my initial step is to ascertain the perspective of the drawing. A head-on view of a building’s exterior implies it’s a facade drawing. An overhead view could suggest a site plan, or if it presents a cross-section of the building, a section drawing. The illustration of structural components and measurements might indicate a structural drawing. Lastly, if the layout exposes specific rooms, it’s probably a floor plan. This methodology assists me in sorting the blueprint into one of five classifications: facade drawing, site plan, section drawing, structural drawing, or floor plan. Therefore, the image shows a {floor plan, section drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A diagram demonstrating the arrangement of rooms within a building at a particular level and the key structural components of a building. 
AI: When examining an architectural blueprint, I first determine the drawing’s perspective. A direct view of a building’s facade suggests it’s a facade drawing. A bird’s eye view could imply a site plan, or if it displays a cross-section of the building, a section drawing. The depiction of structural elements and measurements might point towards a structural drawing. Finally, if the layout reveals distinct rooms, it’s likely a floor plan. This approach aids in categorizing the blueprint into one of five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, the image shows a {floor plan, structural drawing}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A blueprint showing the structural elements of a building. 
AI: I try to identify the load-bearing walls and columns in the building. This view typically shows the building’s structure as if seen from above. Next, I look for the size and type of structural elements. These are usually represented by different shapes and symbols. I then look for any special features like beams or trusses. These are usually represented by specific symbols. Finally, I look for labels and notes that provide additional information about the structural elements. These help me understand the building’s structural system. Based on this, the image provided is a {structural plan}.

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI:  I try to identify the building’s main features and their proportions. This view typically shows the front or side of a building as if seen from straight on. I look for the overall shape of the building, including the roof. Next, I look for details such as windows and doors, which are usually represented by rectangles or squares. I also look for architectural elements like columns or balconies, which have their own specific shapes and sizes. I then look for textures that represent the building materials. These can be represented by different types of lines or patterns. Based on this, The blueprint in the image is a {facade drawing}

Based on the image, what blueprint(s) are there? The blueprint(s) could include an elevation drawing, a floor plan, a site plan, a section drawing, or a structural drawing. Type your final answers like this: “{answer}”

Prompt 4:

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A plan showing the layout of a property or a site. 
AI: I try to identify the boundaries of the site and any existing structures or features. This view typically shows the entire property as if seen from above. Next, I look for the proposed building footprint and any other structures like driveways or walkways. These are usually represented by different shapes and lines. I then look for landscaping elements such as trees, gardens, or water features. These are usually represented by specific symbols. Based on this, the architectural blueprint in the image is a {site plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing that shows a cross-section of a building. 
AI: I try to identify the cut line through the building that shows the most detail. This view typically shows the building as if it were cut along that line. Next, I look for details like floor levels, wall construction, and roof structure. These are usually represented by different types of lines and symbols. I then look for any significant interior features visible in the section. These can include stairs, windows, or furniture. Finally, I look for labels and a scale for reference. These help me understand the size and components of the building. Based on this, the blueprints in the image is a {section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A design plan showcasing the outside appearance of a home and a vertical slice of the building, exposing the internal structure. 
AI:  I try to identify the cut line through the building that shows the most detail, while also recognizing the building’s main features and their proportions. This view typically shows the building as if it were cut along that line, or as if seen from straight on. I look for the overall shape of the building, including the roof structure, and details like floor levels and wall construction. These are usually represented by different types of lines and symbols. Next, I look for details such as windows and doors, which are usually represented by rectangles or squares in the section. I also look for architectural elements like columns or balconies, which have their own specific shapes and sizes. These significant interior features can include stairs, windows, or furniture. Based on this, the architectural blueprints in the a are {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A sketch displaying the layout of rooms at a certain level and the exterior aspect of a residence.
AI:  I try to identify if it’s a bird’s-eye view of the layout of the building or a facade drawing. These views typically show the arrangement of rooms within the building as if seen from above, or the front or side of a building as if seen from straight on. I look for the overall shape of the building, including the roof, and walls, which are usually represented by thick lines. Spaces between these walls indicate rooms. Next, I look for symbols that represent doors and windows. In a bird’s eye view, doors are typically shown as a straight line (the door itself) and an arc that shows the door’s swing direction. Windows are usually represented by a break in the wall with a thin line through it, or by rectangles or squares in a facade drawing. Based on this, the blueprints show a {floor plan, facade drawing}.


Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”

Prompt 5:
Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A blueprint showing the layout of a building at a particular level and a vertical cut through the building. 
AI: When I first look at an architectural blueprint, I try to identify the perspective from which the drawing is made. This can be either of a front or side view which means it is likely a facade drawing. Another perspective is a bird's eye view, which can give me clues whether it is a site plan or a cut-through view which would signal to be a section view. There are also structural elements which can give me clues on what perspective it is, or even if there are measurements in the blueprint hinting towards a structural view altogether. Lastly, I can try to identify whether the layout shows any visible rooms, which would indicate that it is a floor plan. This helps me categorize the blueprint into one of the five types: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, the architectural blueprints in the image show a {floor plan, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A diagram demonstrating the arrangement of rooms within a building at a particular level and the key structural components of a building. 
AI: Upon first glance at an architectural blueprint, I discern the viewpoint of the drawing. A straight-on view of a building’s front or side suggests a facade drawing. A top-down perspective could indicate a site plan or, if it reveals a cut-through view of the building, a section drawing. The presence of load-bearing elements and measurements might hint at a structural drawing. Lastly, if the layout unveils distinct rooms, it’s likely a floor plan. This process helps me classify the blueprint into one of five categories: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, This is a {floor plan, structural drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A detailed sketch showing the front view of a building. 
AI: I try to identify the building’s main features and their proportions. This view typically shows the front or side of a building as if seen from straight on. I look for the overall shape of the building, including the roof. Next, I look for details such as windows and doors, which are usually represented by rectangles or squares. I also look for architectural elements like columns or balconies, which have their own specific shapes and sizes. I then look for textures that represent the building materials. These can be represented by different types of lines or patterns. 



Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A diagram showing the arrangement of rooms on one floor of a building. 
AI: I try to identify if it’s a bird’s-eye view of the layout of the building. This view typically shows the arrangement of rooms within the building as if seen from above. I look for walls, which are usually represented by thick lines, and spaces between them, which indicate rooms. Next, I look for symbols that represent doors and windows. In a bird's eye view, doors are typically shown as a straight line (the door itself) and an arc that shows the door’s swing direction. Windows are usually represented by a break in the wall with a thin line through it. I also look for labels that indicate the names and sizes of rooms. These labels are usually placed within the boundaries of each room. Finally, I look for any fixtures such as sinks, toilets, and furniture. These are usually represented by specific symbols. Therefore, the blueprints in the image show a {floor plan}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: “{answer}”
Image: A drawing showing the exterior view of a building and a section cut through the building, revealing interior structure.
Answer: When I scrutinize an architectural blueprint, my initial step is to ascertain the perspective of the drawing. A head-on view of a building’s exterior implies it’s a facade drawing. An overhead view could suggest a site plan, or if it presents a cross-section of the building, a section drawing. The illustration of structural components and measurements might indicate a structural drawing. Lastly, if the layout exposes specific rooms, it’s probably a floor plan. This methodology assists me in sorting the blueprint into one of five classifications: facade drawing, site plan, section drawing, structural drawing, or floor plan. Based on this, the image therefore shows {facade drawing, section drawing}.

Question: What kind of architectural blueprints can you see in the image? It could be a floor plan, a facade drawing, a site plan, a section drawing or a structural drawing. Type your final answer(s) like this: {answer}
