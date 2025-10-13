# Craft Crew Soul Brews Chronicles

    Step onto the craft crew’s coding trail,
    Where new tales of code set our adventurous sail.
    
    In the Craft Crew Chronicles, side by side we unite,
    To learn and to journey in the coder’s shared light.

## Updates

แต่ถ้าตอนนี้มีไฟ  ช่วยผมลงทะเบียนโดยการ

1) สร้าง fork repo (https://github.com/Soul-Brews-Studio/craft-crew-soul-brews-chronicles/blob/main/batch01/attendees.md) และ 
2) แก้ไฟล์ attendees.md (กด edit ใน github ได้เลย)
3) เปิด pull request กลับมา
4) รอ merge ค้าบ

# Workshop Steps

1) เข้า [https://github.com/soul-brews-hub](https://github.com/soul-brews-hub)
2) แล้ว`สร้าง Repo แบบ Public` ครับ Default จะเป็น Private `แก้เป็น Public ชื่อนำหน้าด้วย เลข Id และชื่อ discord` ใน จากไฟล์https://github.com/Soul-Brews-Studio/craft-crew-soul-brews-chronicles/blob/main/batch01/attendees.md
3) ตัวอย่างเช่น 1-nazt-01-hello-world
    - ถ้าสร้างไม่ได้ให้ลองกดรับ invite และทักถาม Dj BM
4) ไปหน้า github profile ของตัวเอง และสร้าง repo ว่า `workshop-soul-brews`
5) กดสร้าง README.md และกดเปิด Codespace on main และเปิดใน VS Code
6) ลองดู Token ใน repo: https://github.com/Soul-Brews-Hub/z.ai-api-key-for-workshop
    - ถ้าเข้าไม่ได้อันนี้ รอไว้หัดทำคราวหน้า หรือลงทะเบียนรอบถัดไปครับ
7) ลง Claude Code ตาม คำสั่ง npm ใน https://www.claude.com/product/claude-code
8) ก๊อบปี้่เนื้อหา ใน https://gist.github.com/nazt/3f9188eb0a5114fffa5d8cb4f14fe5a4 สร้างไฟล์ใหม่ชื่อ CLAUDE.md
9) ลองเปิดใช้งาน Claude Code 2 วิธี
    - ​inline: `CLAUDE_CONFIG_DIR=~/.claude-zz ANTHROPIC_BASE_URL=https://api.z.ai/api/anthropic ANTHROPIC_AUTH_TOKEN=your_token ANTHROPIC_MODEL=glm-4.5 claude`
    - multiple lines
      ```
      export CLAUDE_CONFIG_DIR=~/.claude-zz
      export ANTHROPIC_BASE_URL=https://api.z.ai/api/anthropic
      export ANTHROPIC_AUTH_TOKEN=your_token
      export ANTHROPIC_MODEL=glm-4.5
      ```
    - alias in .bashrc
      ```
      alias claudez='CLAUDE_CONFIG_DIR=~/.claude-zz ANTHROPIC_BASE_URL=https://api.z.ai/api/anthropic ANTHROPIC_AUTH_TOKEN=your_token ANTHROPIC_MODEL=glm-4.5 claude .'
      ```
      โหลดไฟล์ใหม่: source ~/.bashrc
      run claudez ใช้ได้เลยครับ
11) สั่ง claude code ว่า `commit and push`
10) สมัคร สมาชิก vercel.com

## Attendees

- [Batch 01 Attendees](batch01/attendees.md)
