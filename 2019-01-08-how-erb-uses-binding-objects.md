---
date: 2019-01-08T14:25:14.682141Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/101381407658876898"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1082644397060169729"]
---
How ERB uses `Binding` objects:

    class DiyErb
      def initialize(template)
        @template = template
      end

      def result(binding)
        @template.gsub(/<%=(.+?)%>/) do
          binding.eval($1)
        end
      end
    end

<https://blog.appsignal.com/2019/01/08/ruby-magic-bindings-and-lexical-scope.html>
