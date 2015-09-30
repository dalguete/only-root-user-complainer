# only-root-user-complainer
Complains when no regular user is found. **Don't use root at all!!!**

Yeah, nowadays you can use root in "safer" envs, like containers, and be sure it
won't break anything (maybe?). Or you can say "hey!, it's just in my local, it's harmless".

Turning that into a "normal way of doing things" can be really dangerous.

Sooner or later you'll get use to access as root to many places, maybe a prod env,
or your very same local dev env, and because of a typo or an inocent mistake, you can
blow things up. It's all about culture.

Despite the fact of being repetitive repetitive repetitive, it's **ALWAYS ALWAYS
ALWAYS safer to NOT USE root**. It's less error prone.

**root** is a user to treat with SUPREME CARE. Better use another user and use helpers
as **sudo** to scalate privileges in certain tasks.
That's what this script will do. Remind you to do so, so please, be consider and
**STOP USING ROOT!!!**. There are millions of sysadmins that will thank you with
their hearts for that.

