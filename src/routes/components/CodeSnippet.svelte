<pre class="shiki"><code
		><span class="line"
			><span style="color: #F97583;">using</span><span style="color: #E1E4E8;">&nbsp;</span><span
				style="color: #B392F0;">Schema</span
			><span style="color: #E1E4E8;">;</span></span
		>
<span class="line"
			><span style="color: #F97583;">using</span><span style="color: #E1E4E8;"></span>&nbsp;<span
				style="color: #B392F0;">UnityEngine</span
			><span style="color: #E1E4E8;">;</span></span
		>
<span class="line"></span>
<span class="line"
			><span style="color: #F97583;">public</span><span style="color: #E1E4E8;">&nbsp;</span><span
				style="color: #F97583;">class</span
			><span style="color: #E1E4E8;">&nbsp;</span><span style="color: #B392F0;">DebugLog</span><span
				style="color: #E1E4E8;"> : </span><span style="color: #B392F0;">Action</span><span
				style="color: #E1E4E8;"> &lbrace;</span
			></span
		>
<span class="line"
			><span style="color: #E1E4E8;">&nbsp;</span><span style="color: #F97583;">public</span><span
				style="color: #E1E4E8;">&nbsp;</span
			><span style="color: #F97583;">string</span><span style="color: #E1E4E8;">&nbsp;</span><span
				style="color: #B392F0;">message</span
			><span style="color: #E1E4E8;">;</span></span
		>
<span class="line"></span>
<span class="line"
			><span style="color: #E1E4E8;">&nbsp;</span><span style="color: #F97583;">public</span><span
				style="color: #E1E4E8;">&nbsp;</span
			><span style="color: #F97583;">override</span><span style="color: #E1E4E8;">&nbsp;</span><span
				style="color: #B392F0;">NodeStatus</span
			><span style="color: #E1E4E8;">&nbsp;</span><span style="color: #B392F0;">Tick</span><span
				style="color: #E1E4E8;">() &lbrace;</span
			></span
		>
<span class="line"
			><span style="color: #E1E4E8;">    Debug.</span><span style="color: #B392F0;">Log</span><span
				style="color: #E1E4E8;">(message);</span
			></span
		>
<span class="line"
			><span style="color: #E1E4E8;"></span><span style="color: #F97583;">    return</span><span
				style="color: #E1E4E8;"> NodeStatus.Success;</span
			></span
		>
<span class="line"><span style="color: #E1E4E8;">  &rbrace;</span></span>
<span class="line"><span style="color: #E1E4E8;">&rbrace;</span></span>
<span class="line"></span></code
	></pre>
