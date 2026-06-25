# All In One MLM PHP Script

NexMLM is a complete, white-label PHP MLM platform that covers every major compensation plan in a single deployable codebase. Rather than buying a separate script for each plan type, NexMLM ships with Binary, Unilevel, Forced Matrix, Board Cycling, Generation, and Hybrid plan engines — all switchable from the admin panel with no code changes required.

The platform is built on raw PHP 8.1+ with a clean MVC structure, MySQL 8.0, and Bootstrap 5. It includes a full member dashboard, interactive D3.js genealogy tree, E-Pin activation system, multi-method withdrawal flow, KYC document verification, rank auto-evaluation, and a commission engine built on the Strategy design pattern — one PHP class per plan, fully isolated and extensible.

NexMLM is sold with 100% unencrypted source code, no domain restrictions, and a commercial license that allows deployment on unlimited projects.

<img src="https://www.coderobotics.com/frontend/assets/icon/nexmlm_6_plans_one_platform_mlm_script.jpg">

<b>Compensation Plans</b>
 
<ul>
<li><b>Binary Plan</b>
Each member has exactly two legs — left and right. Commissions are paid based on pair matching of the weaker leg's volume. Includes carry-forward balance, configurable daily cap in USD, matching bonus for the sponsor, and a daily cron job for automated pair processing.
</li>
<li><b>Unilevel Plan</b>
Unlimited direct recruits at level 1. Commissions are paid across up to 8 configurable depth levels, with a separate percentage rate per level set by the admin. The simplest plan structure to explain to members and the easiest to deploy as a standalone.</li>

<li><b>Forced Matrix Plan</b>
Fixed width × depth structure, for example 3×9. Members fill positions via depth-first spillover when a row is complete. Matrix completion triggers a configurable cycle bonus payout. Width and depth are both admin-configurable without code changes.</li>

<li><b>Board Cycling Plan</b>
Members enter boards that split automatically when all seats are filled. The top member cycles out with a reward and re-enters a new board. Remaining members seed the two new boards. Board size, cycle reward amount, and re-entry behavior are all configurable from admin settings.</li>

<li><b>Generation Plan</b>
Rank-based generational overrides. A new generation begins when a downline member achieves the same rank as the upline. Commission percentage is paid per generation, up to 5 generations deep. Works in combination with the auto-rank evaluation engine.</li>

<li><b>Hybrid Plan</b>
Runs two plans simultaneously on the same network. The most common combination is Binary + Unilevel. Both engines execute on every package purchase and commissions from both plans are merged into the member's single wallet. Configured via the admin settings JSON panel.</li>
</ul>

<b>Live demo and download link:</b><br>
https://www.coderobotics.com/product/all-in-one-mlm-php-script
