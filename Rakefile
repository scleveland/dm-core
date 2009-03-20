#!/usr/bin/env ruby
require 'pathname'
require 'rubygems'
require 'rake'
require 'rake/rdoctask'

require 'lib/dm-core/version'

ROOT = Pathname(__FILE__).dirname.expand_path

AUTHOR           = 'Dan Kubb'
EMAIL            = 'dan.kubb@gmail.com'
GEM_NAME         = 'dm-core'
GEM_VERSION      = DataMapper::VERSION
GEM_DEPENDENCIES = [
  %w[ extlib      ~>0.9.11 ],
  %w[ rspec       >=1.1.12 ],
  %w[ addressable ~>2.0    ],
]

PROJECT_NAME        = 'datamapper'
PROJECT_DESCRIPTION = 'Faster, Better, Simpler.'
PROJECT_SUMMARY     = 'An Object/Relational Mapper for Ruby'
PROJECT_URL         = 'http://datamapper.org'

require ROOT + 'tasks/hoe'
require ROOT + 'tasks/gemspec'
require ROOT + 'tasks/install'
require ROOT + 'tasks/dm'
require ROOT + 'tasks/doc'
require ROOT + 'tasks/ci'
