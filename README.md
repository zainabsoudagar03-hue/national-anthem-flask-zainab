# Branch · Push · Pull · Merge · Resolve a Conflict
**National Anthem Project — Workshop Edition**

## How This Workshop Works
This is not a taught session. You work through five parts at your own pace. Nothing here is new — you have done all of it across Sessions 1 to 3.

- Three team members today, not four. Each step says WHO runs it — check your terminal prompt every time.
- Each part ends with a CHECKPOINT. Run it and compare the output before moving on.
- If a checkpoint fails, the 'If stuck' line names the usual cause. Try that before asking.
- Use a NEW repository. If your existing one is in a broken state, today does not care.
- Do not rush. Finishing Part 4 properly is worth more than rushing through all five.

**Your Team**
> satish Team Lead owns the repository, merges, resolves conflicts  
> rajesh Developer writes the application and the anthem content  
> ramesh Tester finds problems, fixes formatting and text

**What You Need**
- Your EC2 instance running, with git, python3 and nano installed
- The three Linux users above, able to log in
- Your GitHub account and your Personal Access Token
- Your Session 1–3 lab guides, open for reference

**Score Sheet — Tick Each Checkpoint as You Pass It**
> [ ] Part 0 — Three users configured (10 min)  
> [ ] Part 1 — Repository published and cloned (20 min)  
> [ ] Part 2 — Push and pull between two people (25 min)  
> [ ] Part 3 — Branch, merge, delete (25 min)  
> [ ] Part 4 — Merge conflict created and fixed (30 min)  
> [ ] Part 5 — Undo and recover (only if time) (15 min)

Hand this in at the end. It tells me where the batch actually is, which decides what we do next session.

**Typing Shortcut**
Where a file has several lines, you can paste the whole thing in one go instead of using nano. Both work — use whichever you prefer:
```
cat > filename.txt <<'EOF'
line one
line two
EOF
```
**NOTE:** Type EOF on its own line at the end, with nothing after it. This saves a lot of time on the longer files, and avoids typing mistakes inside nano.

## Final State of This Repository
This repository has been prepared with the complete workshop history:

- Initial anthem line
- Flask app + first stanza
- Second line of the stanza
- Feature branch with second stanza (merged)
- Title conflict created and resolved (bilingual title chosen)

### Run the App
```bash
pip install -r requirements.txt
python app.py
```
Then open http://<your-ec2-public-ip>:5000

---

*This README contains the full original workshop instructions for reference.*
