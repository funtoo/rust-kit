rust-kit
========

This is rust-kit, a Funtoo Linux kit. It is independently-maintained, as
opposed to auto-generated. This kit contains rust-1.32 from Gentoo with some
minor modifications.

Improvements
~~~~~~~~~~~~

Feb 23, 2019 (drobbins) - The virtuals have been improved somewhat. Rust-bin will
be preferred to rust when emerging things that need rust. In addition, cargo's
virtual is simplified so that we only reference dev-lang/rust in one place --
virtual/rust -- rather than in both virtual/rust and virtual/cargo. This
improves maintainability. I also have dev-util/cargo being a symlink to
virtual/cargo, so it will act identically to virtual/cargo when referenced
as a dependency in ebuilds.

=================================
How to Contribute to this Overlay
=================================

Funtoo is now using https://code.funtoo.org for development, so to contribute,
please create a Funtoo account at https://auth.funtoo.org/new and submit a
pull request at code.funtoo.org. Bugs can be submitted to https://bugs.funtoo.org.


See the following video for an introduction to
code.funtoo.org:

.. raw:: html

    <div style="position: relative; padding-bottom: 50.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/V6PfB64oMWo" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

For a whirlwind tour of how to use code.funtoo.org to create your first pull
request, see the following video:

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/W4FqBLgzhVc" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>
