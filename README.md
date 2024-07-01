# Git-Commands
# Git Commands in Bangla

## গিট ইনস্টলেশন এবং প্রাথমিক কনফিগারেশন

sudo apt-get install git     # উবুন্টু বা ডেবিয়ানের জন্য
brew install git             # ম্যাকের জন্য

git config --global user.name "আপনার নাম"   # গিট ইউজারনেম কনফিগার করা
git config --global user.email "আপনার ইমেইল"  # গিট ইমেইল কনফিগার করা

## রিপোজিটরি ম্যানেজমেন্ট

git init   # একটি নতুন গিট রিপোজিটরি তৈরি করা
git clone <repository-url>   # একটি বিদ্যমান রিপোজিটরি ক্লোন করা

## পরিবর্তন ট্র্যাকিং

git add <file-name>   # একটি নির্দিষ্ট ফাইল স্টেজ করা
git add .             # সমস্ত পরিবর্তন স্টেজ করা
git commit -m "কমিট মেসেজ"   # পরিবর্তন কমিট করা

## স্ট্যাটাস এবং ইতিহাস দেখা

git status   # রিপোজিটরির বর্তমান স্টেট দেখা
git log   # কমিট ইতিহাস দেখা

## ব্রাঞ্চিং এবং মার্জিং

git branch <branch-name>   # নতুন ব্রাঞ্চ তৈরি করা
git checkout <branch-name>   # একটি ব্রাঞ্চে পরিবর্তন করা
git merge <branch-name>   # দুটি ব্রাঞ্চ মিশ করা

## রিমোট রিপোজিটরি ম্যানেজমেন্ট

git remote add origin <repository-url>   # রিমোট যোগ করা
git remote -v   # রিমোট দেখানো
git fetch   # রিমোট রিপোজিটরি থেকে ডেটা আনা
git pull   # রিমোট রিপোজিটরি থেকে ডেটা আনা এবং মেশ করা
git push origin <branch-name>   # পরিবর্তন রিমোট রিপোজিটরিতে পাঠানো

## পরিবর্তন পূর্বাবস্থা ফিরিয়ে আনা

git reset <file-name>   # একটি নির্দিষ্ট ফাইল রিসেট করা
git reset --hard   # সমস্ত পরিবর্তন রিসেট করা
git revert <commit-id>   # একটি পূর্বের কমিট পূর্বাবস্থায় ফিরিয়ে আনা

## অস্থায়ীভাবে পরিবর্তন সংরক্ষণ করা

git stash   # পরিবর্তনগুলো অস্থায়ীভাবে সংরক্ষণ করা
git stash pop   # সংরক্ষিত পরিবর্তনগুলো পুনরুদ্ধার করা

