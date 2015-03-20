# cucumber-shortcake

This is a tool for developing with cucumber.

This is just based off my needs, so if someone were to actually read this,
and want something added...   

There are no dependencies other than Ruby.

Put in ~/bin/ and run from the root of your cucumber test repo.
Two possibilities to use...

shortc features/foobar.feature # This runs every test up UNTIL foobar.feature

shortc features/foobar.feature + # With the plus, it runs all features INCLUDING foobar.feature

This doesn't invoke rake, just cucumber feature1.feature feature2.feature and so on.
