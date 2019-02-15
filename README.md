# DOCFX-Sample
Sample for DocFX: Combine conceptual and reference information in the left-side nav bar

**DocFX Version Used**: 2.40.10

**Template used**: `statictoc` 

**Steps to Reproduce**:

created a combination of conceptual and reference information in left-side nav bar as described in 
https://dotnet.github.io/docfx/tutorial/walkthrough/walkthrough_create_a_docfx_project_2.html

**Actual Behavior**:
When selecting an item in the left side bar, navigation to this page takes place, but the tree collapses and the selection is gone.

**Expected Behavior**:
after navigation to the selected item, the tree and the selection should stay intact,
as it does when using the "default" template.

**More Informations**:
- This only  happens, when conceptual and reference information are combined.
- If I only have reference information it works fine with statictoc. 
- If I use "default" template it also works fine, so I assume my project settings are correct.
- there is no difference if I access it via http: or via file:
