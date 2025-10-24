
Changes made (2025-10-23):
1) Symmetric left-right expansion like XMind for root children.
   - Implemented applySymmetricLayout(root): first half of Level-1 topics go to the RIGHT (top→bottom order), 
     remaining topics go to the LEFT (order reversed) so the overall order is CLOCKWISE by Markdown order.
2) Direction inheritance for deeper levels: children follow the side (left/right) of their parent branch.
   - This keeps entire branches on one side like XMind.
3) No UI changes required; works when importing Markdown via parseMarkdown().

How to revert: use mindmap.js.bak in the same folder.
