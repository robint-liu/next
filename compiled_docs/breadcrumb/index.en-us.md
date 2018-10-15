{"meta":"<h2 id=\"guide\">Guide<a href=\"#guide\" class=\"anchor\">#</a></h2><h3 id=\"when-to-use\">When to use<a href=\"#when-to-use\" class=\"anchor\">#</a></h3><p>It is used to inform the user of the current position and the position of the current page in the entire site. It is an auxiliary navigation method and is applicable to a clear and multi-level structure of the website. Each layer of content is a hierarchical ownership relationship, which is convenient for users to return. One or all levels of pages.</p>\n<h2 id=\"api\">API<a href=\"#api\" class=\"anchor\">#</a></h2>","api":"<h3 id=\"breadcrumb\">Breadcrumb<a href=\"#breadcrumb\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>params</th>\n<th>desc</th>\n<th>type</th>\n<th>default</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>children</td>\n<td>Children components, hsould be an Breadcrumb.Item</td>\n<td>custom</td>\n<td>-</td>\n</tr>\n<tr>\n<td>maxNode</td>\n<td>The maximum number of breadcrumbs is displayed and the excess is hidden</td>\n<td>Number</td>\n<td>100</td>\n</tr>\n<tr>\n<td>separator</td>\n<td>Separator, can be text or Icon</td>\n<td>ReactNode</td>\n<td>&lt;Icon type=&quot;arrow-right&quot; /&gt;</td>\n</tr>\n</tbody>\n</table>\n<h3 id=\"breadcrumb-item\">Breadcrumb.Item<a href=\"#breadcrumb-item\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>params</th>\n<th>desc</th>\n<th>type</th>\n<th>default</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>link</td>\n<td>The breadcrumb item link, if this property is set, the node is <code>&lt;a /&gt;</code>, otherwise it is <code>&lt;span /&gt;</code></td>\n<td>String</td>\n<td>-</td>\n</tr>\n</tbody>\n</table>\n"}