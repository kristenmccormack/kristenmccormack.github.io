---
layout: single
classes: wide
title: "Research"
permalink: /research/
author_profile: false
---

<strong><font size = "4">Job market paper</font></strong>
<p style="margin-bottom:0"> Education under extremes: Temperature, student absenteeism, and disciplinary infractions.</p>
<div class="buttonbar">[ <button class="btn btn--light-outline" onclick="button(&quot;abs7&quot;)">abstract</button> | <a href="/files/mccormack_jmp.pdf" target="_blank">paper</a> ]</div>
<div class="popup" id="abs7" style="display: none; margin-bottom:1rem">How does student behavior respond to extreme temperatures and who is most affected? Using daily student-level data from a large urban school district, I estimate the causal effect of temperature on two dimensions of student behavior that are predictive of academic and later life outcomes: school absences and disciplinary referrals. Absenteeism increases in response to both hot and cold conditions, particularly for Black and Hispanic students. Hot conditions also increase the likelihood that a student will receive a disciplinary referral, an effect found only among students attending schools without air conditioning. Results suggest that unequal access to air conditioning may exacerbate racial, ethnic, and socioeconomic disparities in school.</div>


<strong><font size = "4">Publications</font></strong>
<p style="margin-bottom:0">The price of biodiesel RINs and economic fundamentals. (with Scott H. Irwin and James H. Stock)</p>
<p style="margin-bottom:0; color:#666"><em>American Journal of Agricultural Economics, 2020</em></p>
<p style="margin-bottom:0; color:#666"><em>Agricultural & Applied Economics Association Quality of Research Discovery Award</em></p>
<div class="buttonbar">[ <button class="btn btn--light-outline" onclick="button(&quot;abs4&quot;)">abstract</button> | <a href="/files/AJAE_2020.pdf" target="_blank">paper</a> | <a href="https://onlinelibrary.wiley.com/doi/full/10.1002/ajae.12014" target="_blank">html</a> | <a href="/files/AJAE_2020_discussion.pdf" target="_blank">discussion (Bruce A. Babcock)</a> | <a href="/files/AJAE_2020_response.pdf" target="_blank">response</a> ]</div>
<div class="popup" id="abs4" style="display: none; margin-bottom:1rem">The D4 RIN is the tradable compliance certificate for the biomass-based diesel (BBD) mandate in the renewable fuel standard (RFS). Understanding the price dynamics of the D4 RIN is important for understanding the RFS because its price sets a ceiling on the ethanol RIN (D6) and because some observers have suggested that RIN price fluctuations are too large to be explained by economic theory. We use option pricing theory to develop a model of the D4 RIN in terms of its economic fundamentals: the spread between the price of biodiesel and petroleum diesel and the status of the biodiesel blenders’ tax credit. The resulting D4 fundamental price closely tracks actual D4 prices. We conclude that RIN price volatility arises because of the design of the RFS and intrinsic features of the U.S. fuel supply system.</div>


<p style="margin-bottom:0">The roles of energy markets and environmental regulation in reducing coal-fired plant profits and electricity sector emissions. (with Joshua Linn)</p>
<p style="margin-bottom:0; color:#666"><em>RAND Journal of Economics, 2019</em></p>
<div class="buttonbar">[ <button class="btn btn--light-outline" onclick="button(&quot;abs3&quot;)">abstract</button> | <a href="/files/RAND_2019.pdf" target="_blank">paper</a>  | <a href="https://onlinelibrary.wiley.com/doi/10.1111/1756-2171.12294" target="_blank">html</a> ]</div>
<div class="popup" id="abs3" style="display: none; margin-bottom:1rem">Between 2005 and 2015, US electricity sector emissions of nitrogen oxides and sulfur dioxide, which harm human health and the environment, declined by two thirds, and many coal-fired power plants became unprofitable and retired. Intense public controversy has focused on these changes, but the literature has not identified their underlying causes. Using a new electricity sector model of the US eastern interconnection that accurately reproduces unit operation, emissions, and retirement, we find that electricity consumption and natural gas prices account for nearly all the coal plant profitability declines and resulting retirements. Environmental regulations had little effect on these outcomes.</div>


<p style="margin-bottom:0">Consignment auctions of free emissions allowances. (with Dallas Burtraw)</p>
<p style="margin-bottom:0; color:#666"><em>Energy Policy, 2017</em></p>
<div class="buttonbar">[ <button class="btn btn--light-outline" onclick="button(&quot;abs3&quot;)">abstract</button> | <a href="/files/EnergyPolicy_2017.pdf" target="_blank">paper</a>  | <a href="https://www.sciencedirect.com/science/article/pii/S0301421517302665" target="_blank">html</a> ]</div>
<div class="popup" id="abs3" style="display: none; margin-bottom:1rem">While the initial distribution of emissions allowances is usually thought to be independent of the emissions outcome, free allocation can affect the efficiency and fairness of allowance trading. Inefficiency may result from thin allowance markets, poor price discovery, and regulatory or organizational complexities that hinder the recognition of opportunity costs. Concerns about fairness may result from intransparency in the process of transferring substantial allowance value. We explore the role of consignment auctions in mitigating these concerns. These revenue-neutral auctions return the financial value of allowances to their original holders while revealing prices and directing allowances to their highest-valued use. They also can be used to support a minimum price when allowances are freely distributed, which may facilitate program linkage. Consignment auctions have minimal administrative costs and do not necessarily involve government. Experience indicates that they can play an important role, especially in new markets.</div>


<script>
function button(id) {
  var x = document.getElementById(id);
  var ids = ["abs3", "abs4", "abs7"];
  for(var i = 0; i < ids.length; i++) {
    var item = ids[i];
    if (item != id) {
      document.getElementById(item).style.display = "none";
    } else {
      if (x.style.display === "none") {
        x.style.display = "block"
      } else {
        x.style.display = "none";
      }
    }
  }	
}
</script> 

<script>
document.querySelectorAll('.bracket')
  .forEach(list => {
    const c = list.querySelectorAll('li').length + 1;
    list.style.counterReset = `list ${c}`;
  });
</script>